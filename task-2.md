# Task-1
# configure ur global settings
if ur git and github are not linked u use git config to link it with them 
## for username and email
git config --user.name
git config --user.email
## list all the configs
git config --list

# Task-2
## create a file and then modify and then list the difference
echo "diff">file.txt
git add .
git commit -m "diff"
echo "first github file">>file.txt
git add .
git status
git diff

# Task-3
## Undoing changes
### unstaged a staged file
git reset file1.txt
### it will unstage an staged file
## discard the worked changes
git checkout -- file1.txt



# Task-4
## Verify the remote
git remote -v


# Task-5
## Ignoring files
echo "ignored file">.gitignore
git add .gitignore
git commit -m "Added Ignore"
git status to see if the file is not staged then ignored or error



# Task-6
## Remove Untracked files
git clean -f



# Task-7 
## Create an alias for frequently used file
git config --global alias.st status
git config --global alias.cm commit
## Use the alias
git st
git cm -m "Message"
