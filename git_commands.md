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
git remote add origin <web address>

Renaming branch:
git branch -M main 

Uploading file to GitHub project page:
git push -u origin main

the "-u" is needed when file is added to GitHub for the first time.


Getting file sync from GitHub:
git pull


Downloading file from GitHub:
git clone <repo link>

Folder name can be changed by simply adding the desired folder name after the GitHub repo link