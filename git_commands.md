## Config commands (name, email)
Name:
git config --global user.name
Email:
git config --global user.email

## Git file control
Initialization:
git init
(folder will be hidden)

git status
(see files)

Add files:
git add <file>

examples...

Add all files in folder:
git add .


## Commit
Commit file:
git commit -m "Comment"

note: if no comment was added with -m, git will open default text editor in order to add commit comment

## Uploading / Updating project to GitHub
Adding GitHub page to project: 
git add origin <web address>

Renaming branch:
git branch -M main 

Uploading file to GitHub project page:
git push -u origin main

Downloading file update from GitHub:
git pull