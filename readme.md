# github setup in machine
### git config --list
+ list github credentials
### git config --global user.username your_ username
### git config --global user.email your_ email

# Pushing code to github
1.0 First time pushing 
### git init
+ Initialized empty Git repository 
###  git add .
+ add all changes made in your projec folder into the Initialized empty Git repository 
### git commit - m"commit message"
+ message of the changes made
### git remote add origin your_github_repo_link
+ it connects local repository with remote repository on github
### git remote -v
+ confirms whether the local and remote repositories have connected successfully
### git push origin master (name of your branch)
+ adding or pushing all the changes earlier made in your local repository to your remote repository


2.0 subsequent pushing
###  git add .
+ add all changes made in your projec folder into the Initialized empty Git repository 
### git commit - m"commit message"
+ message of the changes made

### git push origin master (name of your branch)
+ adding or pushing all the changes earlier made in your local repository to your remote repository
### git status
+ confirming changes not added
+ by john

