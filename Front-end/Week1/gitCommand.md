## Git Commands

- initializing the folder as a Git repository

    ```
    git init
    ```

- Set the local Git repository to set its remote origin

    ```
    git remote add origin <repository URL>
    ```

- Checking the status of Git repository 

    ```
    git status
    ```

- Adding files to staging area

    ```
    git add .
    ```

- Committing the current staging area to Git repository

    ```
    git commit -m "xxxxx"
    ```

- Pushing your commits to the online repository

    ```
    git push
    git push -u origin master
    ```

- Checking the log of the commits

    ```
    git log
    git log --oneline
    ```

- Discarding out a file from an earlier commit

    ```
    git checkout <commit's number> <file name>
    ```

- Resetting the Git repository
  
    Use git reset to reset the staging area to the last commit without disturbing the working directory.


    ```
    git reset HEAD <file name>
    ```

- Cloning an online repository
  
    ```
    git clone <repository URL>
    ```
