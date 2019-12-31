# Git Notes

Command                    | Description
-------------------------- | ---------------------------
`git add .` | to add files of the current directory to the index
`git commit --amend` | to add the changes to the last commit
`git checkout <filename>` | to cancel the changes for a file
`git checkout -b <branch>` | to create and switch to a new branch
`git branch -d <branch>` | to delete a branch
`git pull` | to pull changes from the remote repository
`git push` | to push changes to the remote repository
`git status` | to show status (changed files, files to add to the current commit 
`git diff <filename>`| to show difference in the file between current and previous states 
`git reflog expire --expire-unreachable=now --all` |  removes all references of unreachable commits in `reflog`
`git gc --prune=now` | removes commits without references in `reflog`
`git rebase -i HEAD~3` | rebases the last 3 commits in the interactive mode 
`git clone --depth=1  <repo> | clone the last revision

