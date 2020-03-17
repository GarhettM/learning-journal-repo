Git is a DVCS that stored data in a file system made up of snapshots.
  - Every saved change is called a "commit"
  - Git relies on local information mostly. Its main role is a cloud storage or "repository"
  - Git will detect corruptions
  - Files in Git can reside in three main states: committed (data is secured and stored in local), modified (file is changed but not committed), and staged.
  
  Some git code
  - Importing `cd name` then use `git init` this creates a subdirectory named .git
  - To track these `git add *.c` then `git add LICENSE` then `git commit -m "any message here"`
  - Cloning a repository `git clone http://locvatiofrepository.com
  - to clone into a repository `git clone http://locationofrepository.com mydirectory
  
  The local Git repository has three components:
    - Working Directory: The actual files reside here.
    - Index: The area used for staging
    - Head: Points to the most recent commit
    
    ![Image](https://www.udemy.com/blog/wp-content/uploads/2015/08/image036.png)
    
    To determine the state og a file use `git status`this will show the branch wim on and shows any changed files.
    - to switcch to or "track" a new repository use `git add filename`
    - to track all files in a repository, use `git add *`
    
    `git commit -m "message of changes here"
    In order to push chnges to remote repository use `git push origin master`
    
    If im working on changes but don't want to commit them yet I can use `git stash` to hide changes and then use `git stash apply` to get them back
    
    
   `git remote` and `git remote -v` will show all the remote repositories
   - start with `cd filename`
   - then use `git remote -v`
   - to add a remote repo `git remote add shortname url`
   
    
    
    
