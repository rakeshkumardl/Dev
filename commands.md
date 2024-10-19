Git Notes
1. Creating Directories and Navigating

bash

mkdir git-for-devops   # Create a directory named 'git-for-devops'
cd git-for-devops/      # Change directory to 'git-for-devops'
pwd                     # Print the current working directory

2. File Operations

bash

touch nibba.txt         # Create a new empty file named 'nibba.txt'
touch nibbi.txt         # Create a new empty file named 'nibbi.txt'
ls                      # List files and directories in the current directory
ls -l                   # List files in long format, showing permissions, size, etc.
ls -a                   # List all files, including hidden files
rm nibbi.txt            # Remove 'nibbi.txt'
cat rakesh.txt          # Display contents of 'rakesh.txt'

3. Git Initialization

bash

git init                # Initialize a new Git repository in the current directory

4. Adding and Staging Files

bash

git add nibbi.txt       # Stage 'nibbi.txt' for commit
git add nibba.txt       # Stage 'nibba.txt' for commit
git add .               # Stage all changes (new files, modifications, deletions)

5. Status Checks

bash

git status              # Check the status of your working directory and staging area

6. Committing Changes

bash

git commit -m "nibba,nibbi add"    # Commit staged changes with a message
git commit -m "new file added"     # Commit with a message describing new files added
git commit -m "new changes are done" # Commit describing changes that were made
git commit -m "added nibbu"        # Commit describing the addition of 'nibbu.txt'

7. Unstaging and Restoring Files

bash

git rm --cached nibba.txt  # Unstage 'nibba.txt' (but keep the file locally)
git restore nibbi.txt      # Restore 'nibbi.txt' from the latest commit
git restore rakesh.txt     # Restore 'rakesh.txt' after removing it

8. Creating and Switching Branches

bash

git checkout -b Dev        # Create a new branch named 'Dev' and switch to it
git checkout master        # Switch back to the 'master' branch
git branch                 # List all branches in the repository

9. Logging History

bash

git log                    # View the commit history
git log --oneline           # View commit history in a simplified, one-line format
history                    # Display the command history (bash shell command)

10. Configuration

bash

git config --global user.name "rakeshkumardl"          # Set global Git username
git config --global user.email "rakeshkumar15041989@gmail.com" # Set global Git email

Summary of Common Git Commands

    git init: Initializes a new Git repository.
    git status: Checks the status of the repository (modified, staged, etc.).
    git add: Stages files for commit.
    git commit: Commits staged files to the repository with a message.
    git rm --cached: Removes a file from staging without deleting it from the working directory.
    git restore: Restores files to a previous state.
    git checkout: Switches between branches.
    git branch: Manages and lists branches.
    git log: Views the commit history.
