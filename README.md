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
`$ git commit -m "<commit message>"` - saves staged file changes. Record changes to the repo.

#### Branching
`$ git branch <branch name>` - creates a specific branch

`$ git branch` - git-branch - List, create, or delete branches

`$ git checkout <branch name>` - moves you to that branch to "check it out" and work on it.

#### Merging

`$ git merge <branch name>` - Join two or more development histories together. Branches meet up again to become one.
#### Commands for working with a remote repository (e.g. Github)

`$ git clone <repo path or URL>` - clone a repository into a new directory.

`$ git remote` - List all remotes for the current repo.

`$ git remote add <remote name> <remote path or URL>` - adds a remote to your repo.

`$ git pull <remote name> <branch name>` - Pull down changes from a remote and integrate them into your repo. Performs `git fetch` and then `git merge`.

`$ git push <remote name> <branch name>` - Send your changes to the remote to be merged.