# Task 1
# How to do multiple Commit
create a file using echo then add it and commit it
now append the file and edit it and add and make second commit 
here's how u do multiple commit

#
 Task 2
# 
How to check commit history and status
## 
for status of the files
git status = to check the status of the files
## 
for Commit history
git log =to check commit history u will do git commit


# 
Task 3 
## 
for accessing commits in oneline 
git log --oneline
## 
for accessing commit with graph
git log --graph
## 
to access additonal information abt Commit
git log --decorate


# Task 4
# Create a clone from a repository 
git clone <link of the repo>


# Task 5
# How to create a new branch and shift to it
## create  new branch
git branch <branch name>
## shift to that new branch 
git checkout <branch name>
## create a new branch and shift to it in one step 
git checkout -b <branch name>


# Task 6
# merge the feature branch to the main branch 
git merge <branch name>

# Task 7
# Merge Conflict
git branch-A
git branch-B
### Modify the same line in README.md of both the branches
### Now merge the branches
git merge branch-A
git merge branch-B
### when we will merge the branches branch-A will merge but branch-B will open a merge conflict
### to solve that u will use esc and then :w and write and then :q



# Task-8
# Rename a branch & delete a branch 
## to rename
git branch -m <old-branch-name> <new-branch-name>
## to delete = git branch -d <branch-name>


# Task-9
# git stash and its details
## git stash is used to temporary save a file which ur not confirm to commit or to upload
git stash
## git stash apply is used to re-apply the changes which u have temporary saved 
git stash apply 
## to find the list of the stashed files
git stash list
## to delete the stash after all the works
git stash drop



# Task-10
# git rebase and its function 
it takes the commits from your current branch and moves them to another branch's tip
## git rebase -i
Interactive Rebase (git rebase -i)
Lets you choose how to modify commits (reorder, squash, edit, etc.).
### git rebase -i HEAD~3
it will show u the recent 3 commits u have done
in place of i u can put reorder squash edit 
### git rebase --continue it will help u continue the task after resolving conflict
### git rebase --abort if a rebase goes wrong it will abort that rebase



# Task-11
# git checkout -b cherry-picking
git checkout cherry-pick <commmit hash>
### by git cherry-pickk we can clone a particular commit 



# Task-12
## Tagging commits
by git tag <tag name> <commit hash>
by git push --tags we can push it

