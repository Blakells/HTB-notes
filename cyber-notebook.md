apropos [command] find all pages of that command and a brief description 


Section 7/ 30 - Navigation 

*ls* only displays files and folders only 
*ls -l* displays the long form data of each file 
*ls -la* is list all 

you can also specify the path after the ls argument to list a specific directory path 
a single dot represents the current directory 
two dots represent the parent directory 
*clear* clears the shell

Section 8/30 - Working with Files and Directories 

*touch* creates a file 
*mkdir* creates a folder
To move a file from one directory to another: Blakells@htb[/htb]$ mv <file/directory> <renamed file/directory>

To rename a file you use the mv command but don't specify a directory, just two names like so: "Blakells@htb[/htb]$ mv info.txt information.txt"

to move files to a specific directory, the arguments are mv [file name] [new file name] [directory path]

to copy a file you'd say cp [path/file] [path]

Section 9/30 - Editing Files 

*nano* is the file editor that's most common 
vim is also another one 

honestly it looks like most nano instructions are fairly self explanatory 

I don't really like VIM based on my first impressions of it

Section 10/30 - Find Files and Directories 