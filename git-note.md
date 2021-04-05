# Clone from github to local:
Open the folder you wanna pull your files into

Use the following command to clone:
> $ git clone SSH OR HTTPS link

Use the following command to change directory to the git directory
> $ cd THE FOLDER NAME

Use follwing command to check if there is a .git file in there to determine if you are in git directory
> $ ls -la 

# Add files
> $ git add FILE NAME OR . FOR ALL FILES

# Commit changes
> $ git commit -m "FIRST DESCRIPTION" -m"SECOND DESCRIPTION"

# Push to github for files pulled from github
> $ git push origin master

# Push to github for files started locally
Go into the directory you wanna make it a git repository to:
> $ cd FILE NAME

## Make this directory a git repository (when inside the directory):

> $ git init

## Then add file:
> $ git add

## Commit changes:
> $ git commit-m "XXX MESSAGE" -m"XXX DESCRIPTION"

## 1. Then go to github to create a new repository **named exactly the same** as the git directory on local

## 2. Copy the SSH or HTTPS link from github repo page

## 3. Add reference to the remote repository on github using following command:
> $ git remote add origin SSH OR HTTP link

## 4. Check what remote repositories that are connected to this repo using command:
> $ git remote -v

## 5. Push to github:
> $ git push origin master

### shortcut for git push origin master:
> $ git push -u origin master

# Check out branch you have (* indicates the current branch you are in)
> $ git branch

# Creating a new branch
> $ git checkout -b BRANCH NAME

# Switching between branches
> $ git checkout BRANCH NAME

# Check out the difference between two branches
## Switch to the master branch
> $ git checkout master

## Check difference
> $ git diff NAME OF THE NEW BRANCH

# Push branch to github
> $ git push -u origin YOUR LOCAL BRANCH NAME (AS WELL AS THE BRANCH NAME ON GITHUB)

# Pull changes from github to local master branch again
> $ git checkout master

> $ git pull origin master

# Delete branch locally
> $ git branch -d BRANCH NAME

# Delete branch remotely
> $ git push origin --d REMOTE BRANCH NAME




































