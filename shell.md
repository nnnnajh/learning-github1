# Note.
***pwd*** : shows the current path in a hierarchical directory   
***cd*** : change directory   
***ls*** : list files and directories  
### shell command: cd and ls  
- / root
- \. current directory
- \.\. upper-level directory
- ~ home of current user
- /\[directory name\]: absolute path
- \./\[directory name\]: relative path
- \.\./\[directory name\]: relative path                   
  
-------------------------
### shell command: More on ls
-ls: List the files in the working directory
-ls \/bin: List the files in the \/bin diretory
-ls -l: List the files the working directory in long format    
  
----------------------------------------
### Manipulation: cp
***cp***: copy files and directories
- cp \[file1\] \[file2\]: Copies the contents of file1 into file2 does not exist, it is created
- cp\-i \[file1\] \[file2\]: Like above however, since the "-i" option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1
-cp \[file1\] dir1: copy the contents of file1 inside of directory dir1.
-cp -r dir1 dir2: Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory named dir1 within diretory dir2.
 
------------------------------------------------
### Manipulation: mv
***mv***: move files and directories or rename them   
-mv \[file1\] \[file2\]: If file2 does not ecist, then file1 is renamed file2.
-mv -i \[file1\] \[file2\]: Like above however, since the "-i" option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1
-
