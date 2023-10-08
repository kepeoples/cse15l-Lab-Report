# **Lab Report 1**

Three basic filesystem commands—cd, ls, and cat—were the focus of today's lab.  
In a Unix-based operating system, these commands are crucial for browsing and working with directories and files.  
I'll present examples of using these commands both without arguments and with paths to directories or files in this report.  

 1) **The 'cd' Command**:  
*(a) Command with no arguments.*    
```$ cd```  
Working Directory: /home/username  
Output: No output  
**Explanation**: The home directory is where you end up when you run cd without any arguments, as explained. My home directory in this instance is /home/username. The command runs without a hitch and doesn't print anything.    
*(b) Command with a path to a directory as an argument.*    
```$ cd /path/to/directory```  
Working Directory: /home/username  
Output: No output  
**Explanation**: Using a directory path as an input to the command cd causes your working directory to be changed to the supplied path. In this illustration, we went from our home directory to /path/to/directory.    
*(c)  Command with a path to a file as an argument.*     
```$ cd /path/to/file.txt```  
Working Directory: /home/username  
Output: Error: Not a directory  
**Explanation**: The cd command does not accept a file path as an argument; instead, it demands a directory path. Since you can only travel to directories, attempting to change to a file path will result in an error.    

 3) **The 'ls' Command**:  
*(a) Command with no arguments.*    
```$ ls```  
Working Directory: /path/to/directory  
Output: List of files and directories in /path/to/directory  
**Explanation**: ls lists the contents of the current directory (in this case, /path/to/directory) when it is used without any arguments. The command outputs a list of the files and directories that are present in the directory that was supplied.    
*(b) Command with a path to a directory as an argument.*   
```$ ls /path/to/another/directory```  
Working Directory: /path/to/directory  
Output: List of files and directories in /path/to/another/directory  
**Explanation**: Using ls with a directory path as an argument allows you to list the contents of a specific directory (/path/to/another/directory in this example).  
*(c) Command with a path to a file as an argument.*    
```$ ls /path/to/file.txt```
Working Directory: /path/to/directory
Output: Error: Not a directory  
**Explanation**: The ls command expects a directory path as an argument, not a file path. Attempting to list the contents of a file path results in an error.

  
 5) **The 'cat' Command**:    
*(a) Command with no arguments.*    
```$ cat```  
Working Directory: /path/to/directory  
Output: Error: No input file  
**Explanation**: The cat command needs a file path as an argument to display a file's content, as explained. Because it is unable to determine which file to display when used without any inputs, an error is generated.  
*(b) Command with a path to a directory as an argument.*  
```$ cat /path/to/file.txt```  
Working Directory: /path/to/directory  
Output: Contents of file.txt  
**Explanation**: The contents of the provided file (in this case, file.txt) are displayed when you run cat with a file path as an option.   
 *(c) Command with a path to a file as an argument.*   
```$ cat /path/to/directory```  
Working Directory: /path/to/directory  
Output: Error: Is a directory  
**Explanation**: A file path, not a directory path, is what the cat program requires as an argument. An error occurs when attempting to display the contents of a directory.  

**Conclusion**  
In this lab report, we looked at several instances for the fundamental filesystem operations cd, ls, and cat.  
We covered the anticipated results and potential mistakes associated with each use scenario, as well as how to use these commands with directory paths, file paths, and no parameters.  
For effective file and directory navigation and manipulation in a Unix-based operating system, understanding these commands is crucial.





