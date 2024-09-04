## Git Commands

#### Git Checkout

* `git checkout filename` : used to revert back to the last commit (snapshot) for the code if the current code is messed up or contains bugs.
* `git checkout -f` : Used to revert back to all files that were modified to the last commit made.

#### Git Log

* `git log` : used to get logs of each commit.
* `git log -p -num` : Shows the number of commits you want to see. {num = number of commit you want to see}.

#### Git diff

* `git diff` :  **Compares working tree with staging area**. If a file is modified, shows the lines/content that are modified in the files.
* `git diff --staged` : Compares the staging area from last commit.
* `git checkout -f` : reverts back to the last commit.

`git checkout -a -m "message"` : Skips the staging area and adds and commits the file directly.

`git rm` : Deletes the file and removes if from staging area.

`git rm --cached` :  removes file from staging area but does not delete it.

`git status -s` : Short hand property for checking the changes in files. Tells us which file is modified in working tree and staging area.

`git branch` : Shows all the branches.

`git branch <branch_name>` : creates a new branch with the branch_name.

`git checkout <branch_name>` : Switches to branch_name.

`git checkout -b <branch_name>` : creates a new branch and switch to that branch.

## Git Remote Repositories

* `git remote` : Shows the remote repositories if any.
* `git remote add origin <url>` : Adds a remote repository as a origin.
* `git remote -v` : Shows the url for fetching and pull requests.
* `git push origin master` : Pushes the master branch to the origin remote repository.
