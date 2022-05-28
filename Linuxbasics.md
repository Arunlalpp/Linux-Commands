# Intro

## Description about the auther 
- man whoami
- man man what are the page do you wnat ?

## Linux Commands
1. pwd 

  - The /root directory is the home directory of the root (administrative) user. If you are logged in as another user.

2. touch 

  - The touch command is a standard command used in UNIX/Linux operating system which is used to create, change and modify timestamps of a file.

3. ls

  - The command to recognizes that we have some files in our home directory

4. man ls 

  - List all the possible commands list

5. ls --all

  - list all the diractory files details 

6. ls -a ls -l

  - list all hoidden or (dot) files 

7. cd 

  - Change diractory 
  - cd ..
  - cd home/ 

8. mkdir

  - To make folders

9. rm 

  - To remove files or directories
  . rm -v to delete selected files from a folders (rm -v car cat bat)

10. rm -R /Foldername

   - remove directories and their contents recursively

   - rm -rv Folder_name
   - To remove all the files from an cntent folder

11. xdg-open

   - To open a folder via terminal

12. mv

  - To rename a files or folder by mv folder_name modified name 

13. mv 

-  To move one folder or files mv folder_name/ to Folder_name/

14. cp cp -r to copy folder

  - copy files and directories

15. head 
 
  - to find howmany linesw are presened in the text file == its not show morethan 100 lines

  - tail , tail -n [10]= lines 
  
  - outpu the last 10 line the text file or last part the file 

16. date 

  - Print the current date 

17. head filename

  - display current date

18. cat 

   - concatenate files and print on the standard output
   - Diplay the text file details 

   - cat text.text text.text > concatinate.txt

18. cat -n 

   - To found all lins in te text    

19. echo 
  
   - To print some text and also to pass arguments to a text file 
   - echo "username=Arun" > config.text
   - echo "KEY=12345678" >> config.text
   - echo {a,b,c} .text
     - checking the combinations b/t the txt

20. wc

  - Counting he maximum number of words in the text files 

  - wc -l number of lines

  - wc text.text text2.txt | wc - l  

21. sort

  - sort lines of text files

22. uniq

  - sort lines of text files
  - sort text.text | uniq 

23.  echo app. {js,html,py,css}

  - create app.js and echo {1..99}

24. diff 

   - compare files line by line

25. find 

  - search for files in a directory hierarchy
  
  - find . -name 'filename'

  - find . -type d -name '*A*'
  
  - find . -type d -name '*.md' -not -path 'node_module';
  
  - find -type f -size +100k -size 1M 
  
  ## find files edited morethan 3 days ago
  
  - find . -type f -mtime +3 

  - You can delete all files matching a search by adding the delete option.This deletes all the files edited in the last 24 hours
  
  - find . -type f -mtime +3 -delete

  ## You can exixute a command on each result of the search. In this example we run CAT to print the file content   


  - find . -type f -exec  cat {} \;

  - notice terminating {} \; is filled with the file name a the execution time  

26. grep

  - You can use grep in search in files or combine it with pipes to filter the output of another command

  - grep document.getElementById index.md   

  - grep -nc 2 document.getElementById index.md 

  - it is usefull for to print 2 lines before, and 2 lines after the matched lines to give us more contex c gives accept the number of lines
  
  - grep -r "Apple"

  - find all possible words in the entail library "Apple" 

27. du 

   - To find size of the machine 

   - du -h notations for human readable 

   - du -m for megabytes

   - du -g for gigabytes

   - du -h | sort -h  

28. df 

  - It is used to find the disk usage information 

  - i basic from will print information about the volume mount 

  - using df -h (Value in human readable)

 29. history 

   -  history  | less
      history | grep "cookies"

30. ps 

  - Your compute is running all time, tons of different process , inspecting them suing this command  

31. top 

   -  Dipslay and update sorted information about the processes

   -  Its used to list the process running in the real time in an dynamical real time information about the realime processin he system 