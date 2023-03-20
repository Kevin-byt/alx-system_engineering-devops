The following scripts are within this directory:

1. 0-current_working_directory --> A script that prints the absolute path name of the current working directory
2. 1-listit --> Display the contents list of your current directory.
3. 2-bring_me_home --> Changes the working directory to the user’s home directory.
4. 3-listfiles --> Display current directory contents in a long format.
5. 4-listmorefiles --> Display current directory contents, including hidden files (starting with .). Use the long format.
6. 5-listfilesdigitonly --> Display current directory contents. Use Long format with user and group IDs displayed numerically and hidden files (starting with .)
7. 6-firstdirectory --> Creates a directory named my_first_directory in the /tmp/ directory.
8. 7-movethatfile --> Move the file betty from /tmp/ to /tmp/my_first_directory.
9. 8-firstdelete --> Delete the file betty. The file betty is in /tmp/my_first_directory
10. 9-firstdirdeletion --> Delete the directory my_first_directory that is in the /tmp directory.
11. 10-back --> Changes the working directory to the previous one.
12. 11-lists --> Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
13. 12-file_type --> Prints the type of the file named iamafile. The file iamafile will be in the /tmp directory
14. 13-symbolic_link --> Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
15. 14-copy_html --> Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
16. 100-lets_move --> Move all files beginning with an uppercase letter to the directory /tmp/u.
17. 101-clean_emacs --> Delete all files in the current working directory that end with the character ~
18. 102-tree --> Creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
19. 103-commas --> Lists all the files and directories of the current directory, separated by commas (,).
        - Directory names end with a slash (/)
        - Files and directories starting with a dot (.) should be listed
        - The listing is alpha ordered, except for the directories . and .. which should are listed at the very beginning
        - Only digits and letters are used to sort; Digits should come first
        - The listing ends with a new line
20. school.mgc --> A magic file that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.