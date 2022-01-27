# ACES Git Workshop
Workshop for ACES Students which serves as an introduction to Git

# Step 1: Local Repository Setup

Navigate to a directory on your computer where you'd like to put this repository and clone it. You can do this by clicking the code dropdown and copying the link for the repository before typing in the following command: 

`git clone <link>`

# Step 2: Creating a Branch

Create your own branch with the following command:

`git checkout -b <super-special-branch-name>`

# Step 3: Adding and Commiting Changes Locally

Create a text file in your branch and put some text in it. The contents of the file do not matter, just that we have a file with information. We can check the status of our workspace with `git status`. This will let us see untracked changes in our local repository.

After this file is created, we can add it to the staging area. We do this with the command `git add <file_name>`. Alternatively, we can also do `git add -A` to add all of our files to staging.

Finally, after adding our file, our final step is to commit it to our local repository. We do this by executing `git commit -m 'message'`. In industry, you want to leave a meaningful message so that your superiors and you yourself can better track what you are doing.

# Step 4: Pushing to Remote Repository

NOTE: THIS WILL NOT WORK IF I DO NOT ADD YOU AS A COLLABORATOR

The first time you push changes for a new branch, you'll need to tell git to establish a remote version of your feature branch. In order to do this we use the following command:

`git push --set-upstream-to origin <branch_name>`

After this, all that is left to do is to run `git push`.



