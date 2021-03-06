# 2021-07-01: Git Basics

- `git init`: initialize git repository in current working directory
- `git status`: gives you the status of the repository
- `git add <FILE>`: adds file to the staging area
- `git commit`: creates a commit; you provide message

- `git log`: how to show what you've done
	- `git log --oneline`: shows one line version of commits

- `HEAD`: where you currently are (the v. of the files on computer
- `git diff HEAD~<NUM> <FILE>`: compares current file to file <NUM> ago
	- `git diff <HASH> <FILE>`: compare current file to <HASH> version

- Use `git status` to find command to unstage or restore file
- `git checkout <HASH> <FILE>`: restore <FILE> to version in <HASH>
	- if you run `git checkout <HASH>` without the <FILE>
	- ...you can fix this by running `git checkout main`

- Use a  `.gitkeep` file to maintain an empty folder in a repo
- Use a `.gitignore` file to remove files or file types from the repo

# Remotes

- `ssh-keygen`: add an SSH key to my system
- `git remote add <URL>`: adds the url
- `git push origin main`: push the main branch to the origin remote
- `git pull origin main`: pull the main branch from the origin remote

## Daniel's GitHub for this course:

https://github.com/chendaniely/2021-07-01-git_basics

N.B.: If you want to use another key, you might have to add it to ssh-agent with a line like this:

`ssh-add ~/.ssh/_id_rsa` assuming that the new ssh key is called `_id_rsa`