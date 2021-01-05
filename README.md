# git-commands 
This repository will contain all important git commands
## Initial configuration commands
1. To configure your git username 
   ```
   git config --global user.name "username"
   ```
1. To configure your git email
   ```
   git config --global user.email "email address"
   ```
1. To check configuration 
   ```
   git config -l
   ```
## Common git commands
1. To initialise git repo
   ```
   git init dirname
   ```
1. To check the changes between the new file and the old file
   ```
   git diff
   ```
1. To check the status of the repo
   ```
   git status
   ```
1. To move the changes from working directory to staging area
   ```
   git add .
   ```
1. To move the changes from staging area to local git repo 
   ```
   git commit -m "commit message"
   ```
1. To upload to changes to the remote github  
   ```
   git push origin main
   ```
1. To see the commit history
   ```
   git log
   ```
1. To reset the changes from staging area to working directory.
   ```
   git reset
   ```