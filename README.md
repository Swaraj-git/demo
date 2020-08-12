# demo
It is a demo project to learn git commands

Steps followed to set local repo, sync local repo with remote and add the local repo changes in remote repo.
1. Create a folder in your  system where you want to create local repo.

2. Create a local repository by follwoing command.
  => git init
  Or 
  If you are using source tree than go to New Tab -> (select) create -> Select the folder where you want to create local repo
  
3. Run the following command to sync the remote repo and local repo
  => git remote add origin "Remote repo url (You can get it on git hub account)"

4. Run following command to pull the data from remote repo
  => git pull origin master
  Note :- Here git is the extension for every git command.
		  pull is the command to get the changes from remote repo
		  origin is shows the remote repo branch
		  master is the branch name of remote repo
		  
5. After run the pull command, if made any changes, you can check the local repo changes by following command.
  => git status
  Note :- This will show 2 type of status.
		  i) Changes done in existing file.
		  ii) New files added in local repo called untracked repo.
		  
6. Command to add the changes in index
  => git add file_name
  or if you have multiple files
     git add -A
  Note :- -A for all files
  
7. Command to commit changes in local repo
  => git commit -m "commit message"  
  or to commit all file changes
     git commit -a -m "commit message"
	 
8. Command to check the log for all commits
  => git log	 