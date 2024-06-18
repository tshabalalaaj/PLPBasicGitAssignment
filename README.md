# PLPBasicGitAssignment

1. GitHub Repository Creation:

    - I Logged in to my GitHub account.
    - Created a new repository called "PLPBasicGitAssignment".
    - Initialize it with a README file.

2. Local Folder Setup:
    -open a terminal or command prompt.
    - cd into the directory where I want to create the Git repository e.g Documents/PLP_Projects.
    - Create a local git folder PLPBasicGitAssignment inside my PLP_Projects folder using mkdir command
    - navigate into the created new Git repository using cd command.
    - command line steps:
    ```
    ctrl + alt + T #to open command line.
    cd Documents/PLP_Projects/
    mkdir PLPBasicGitAssignment
    cd PLPBasicGitAssignment
    ```

3. Git Initialization:
  - Initialized a new Git repository in your local folder.
    ```
    git init
    ```

4. Connecting to GitHub:
  - Linked my local repository to the GitHub repository i created in Task 1.
   ```
    git remote add origin <https://github.com/tshabalalaaj/PLPBasicGitAssignment.git>
   ```

5. Create a File:
  - Inside my local folder, I created a new text file named hello.txt with the greeting message "Hello, Git!".
  ```
  touch hello.txt
  echo "Hello, Git!" > hello.txt
  ```

6. Committing Changes:
  - Stage the changes.
   ```
   git add hello.txt
   ```
  - Commit the changes.
   ```
   git commit -m "Add hello.txt with a greeting"
   ```

7. Pushing to GitHub:
  - Push the committed changes to my GitHub repository.

   ```
   git push -u origin main
   ```