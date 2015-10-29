## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - __Fill Me Out__

#### Repo History
$ git log` - General History of Previous Commits for Repo

`$ git log --oneline --decorate --color --graph --all` - Short, Sweet, and Colorful History of Git Repos

`$ git log -p [filename]` - Very Detailed History of Past Commits for Current Repos

#### Stage files to commit
`$ git add <filename>` - Moves the specified file to the staging area. 

`$ git add -A` - Moves all the files that have been modified to the staging area. 

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - creates a specific branch

`$ git branch` - git-branch - List, create, or delete branches

`$ git checkout <branch name>` - moves you to that branch to "check it out" and work on it.

#### Merging

`$ git merge <branch name>` - __Fill Me Out__
