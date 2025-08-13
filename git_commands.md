## GIT VERSION
git –-version 

## BASIC SETTINGS
git config --global user.name "szalay"
git config --global user.email ”lszalay@rocketsoftware.com"
git config --global init.defaultBranch main
git config --global core.editor "code --wait"

## CHEK SETTINGS
git config --global --list
git config --global --edit

## START
git status
git init
git status

## FIRST PROJECT
create a new file called README.MD

git status

git commit -m "A new README file has been created for the project."

git log
git log -oneline

## Git ignore
.gitignore

### Ignore log files
*.log

# Ignore temp folders
temp/ 
 
*.tmp      # all .tmp files
my?ile.txt # matches my1ile.txt, myAile.txt, etc.
log[0-9].txt # log1.txt, log2.txt, ... log9.txt 


