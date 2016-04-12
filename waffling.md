Waffle 
------
Waffle is a task management system you can use to track the completion of Github
issues.  


Set up an account at waffle.io.  
  
Create issues in your Github repo.  
  
Create a board on Waffle by searching for and selecting your repo.  

In Terminal create a branch to work on an issue and name it beginning with the number of the
issue.  

    git checkout -b 1-setup-project  
When you add, commit and push this branch the issue will move on waffle to in
progress.  
    
When you are done with your branch create a pull request and in the comments of
the request add
    closes #\<issue number>  

When this pull request is merged the task will move to "Done" on your Waffle board.
