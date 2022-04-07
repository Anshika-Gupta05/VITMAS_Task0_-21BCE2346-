# VITMAS_Task0_-21BCE2346-
## Basic Git Commands

1 git config

          git config -global user.name "[name]"
          git config -global user.email "[email address]"
This command sets the author name and email address respectively to be used with your commits.


2 git init

          git init [repository name]
This command is used to start a new repository.


3 git clone
          
          git clone [url]
This command is used to obtain a repository from an existing URL.


4 git add

          git add [file]
This command adds a file to the staging area.
          git add *
This command adds one or more to the staging area.


5 git commit

          git commit -m "[ Type in the commit message]"
This command change the head and records or snapshots the file permanently in the version history with a message.
          git commit -a
This command commits any files you've added with the git add command and also commits any files you've changed since then.


6 git status 

          git status
This command displays the state of the working directory and the staging area.


7 git push 

          git push -u origin master
This command sends the changes made on the master branch, to your remote repository.

8 git pull
  
          git pull
This command will pull everything from the remote server onto your local repository.

9 git branch
   
          git branch
This command lists all the branches available in the local repository.
          git branch [branch_name]
This command creates a new branch.
          git branch -d [branch_name]
This command deletes a branch.

10 git merge 

          git merge [branch_name]
This command is used to merge the spevified branch's history into the current branch.

11 git checkout

          git checkout [branch_name]
This command is used to switch from one branch to another.
          git checkout -b [branch_name]
This command is used to create a new branch and switch to the created new branch.

12 git log

          git log
This command is used to check the commit history in a git repository.

13 git remote
 
          git remote add origin [remote server link]
This command is used to connect your local repository to the remote server.
