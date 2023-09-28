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
- ls: List the files in the working directory
- ls \/bin: List the files in the \/bin diretory
- ls -l: List the files the working directory in long format    
  
----------------------------------------
### Manipulation: cp
***cp***: copy files and directories

### cp
- cp \[file1\] \[file2\]: Copies the contents of file1 into file2 does not exist, it is created.
- cp\-i \[file1\] \[file2\]: Like above however, since the "-i" option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
- cp \[file1\] dir1: copy the contents of file1 inside of directory dir1.
- cp -r dir1 dir2: Copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory named dir1 within diretory dir2.
 
------------------------------------------------
### Manipulation: mv
***mv***: move files and directories or rename them   
- mv \[file1\] \[file2\]: If file2 does not ecist, then file1 is renamed file2.
- mv -i \[file1\] \[file2\]: Like above however, since the "-i" option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1
- mv \[file1\] \[file2\] dir1: The files file1 and file2 are moved to dir1. If dir1 does not exist, mv will exit with an error.
- mv dir1 dir2: If dir2 does not exist, the dir1 is renamed dir2. If dir2 exists, the dir1 is moved within dir2.
-------------------------------------------------------------------------------
### Manipulation: rm
***rm***: delete files and dir
- rm \[file1\] \[file2\]: Delete file1 and file2
- rm -i \[file1\] \[file2\]: Like above however, since the "-i" option is specified, the user is prompted before each file is deleted
- rm -r dir1 dir2: Directories dir1 and dir2 are deleted along with all of their contents
---------------------------------------
### Manipulation: mkdir
***mkdir***: make a new dir
