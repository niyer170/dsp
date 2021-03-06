# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  
 
`pwd__` - show current working directory path  
`mkdir directoryname` - creating a directory  
`rm -r directoryname` - deleting a directory  
`touch filename` - creating a file using `touch` command  
`rm filename` deleting a file  
`mv oldfile newfile` - renaming a file  
`ls -a` - listing hidden files  
`cp oldfiledirectorywithfilename newdirectory` - copying a file from one directory to another  
`output > filename` - renders output to a file  
`cat filename` - output the contents of the file to the console  
 

---  

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  - list the files in the directory  
`ls -a`  - list the files in the directory including those that are hidden  
`ls -l`  - list the files in long format with more information  
`ls -lh` - list the files in human readable long format    
`ls -lah` - list all the files in the directory including those hidden in long human readable format  
`ls -t` - list all the files in the directory by timestamp (newest files first)  
`ls -Glp` - list all files without user owner name in long format in alphabetical order  

---  

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:  

`ls -1` - lists the files in the directory vertically by line  
`ls -R` - lists all files in subdirectories  
`ls -u` - lists files by access time to show which ones have been most recently used  
`ls -F` - lists the files and directories but flags filenames so that you can easily spot files  
`ls -d` - lists only directories for maneuvering large folders with lots of files and only a few directories  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

`xargs` - splits the commands inputted into the prompt into multiple subcommands with modifiers or functions performed on a list of parameters. For example: if I wished to remove multiple files, instead of typing 3 separate commands `rm file1`,`rm file2`,`rm file3`, I can just type `find file1 file2 file3 | xargs rm` and it will find and remove those 3 files.

 

