0-current_working_directory prints the absolute path name of the current working directory.
1-listit display the contents list of your current directory.
2-bring_me_home is a script that changes the working directory to the user’s home directory.
3-listfiles displays current directory contents in a long format.
4-listmorefiles display current directory contents, including hidden files (starting with .).
5-listfilesdigitonly displays current directory contents in long format, with user and group IDs displayed numerically and nd hidden files (starting with .).
6-firstdirectory is a script that creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile moves the file betty from /tmp/ to /tmp/my_first_directory.
8-firstdelete deletes the file betty is in /tmp/my_first_directory.
9-firstdirdeletion deletes the directory my_first_directory that is in the /tmp directory.
10-back changes the working directory to the previous one.
11-lists lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type prints the file named iamafile in the /tmp directory.
13-symbolic_link creates a symbolic link to /bin/ls, named __ls__ in the current working directory.
14-copy_html creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. Also, all HTML files have the extension .html.
100-lets_move creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs deletes all files in the current working directory that end with the character ~.
102-tree creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
103-commas lists all the files and directories of the current directory, separated by commas (,).
school.mgc creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
