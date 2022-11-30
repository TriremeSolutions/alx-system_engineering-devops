0-current-working-Directory: prints the absolute path name of the current working directory

1-listit: Displays the contents list of your current directory

2-bring_me_home: Changes the working directory to the user’s home directory.

3-listfiles: Displays current directory contents in a long format

4-listmorefiles: Displays current directory contents, including hidden files, using the long format.

5-listfilesdigitonly: Displays current directory contents. Long format with user and group IDs .

6-firstdirectory: Creates a directory named my_first_directory in the /tmp/ directory

7-movethatfile: Moves the file "betty" from /tmp/ to /tmp/my_first_directory.

8-firstdelete: Deletes the file "betty" in /tmp/my_first_directory

9-firstdirdeletion: Deletes the directory "my_first_directory" in the /tmp directory.

10-back: Changes the working directory to the previous one.

11-lists: Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type: Prints the type of the file named "iamafile". The file "iamafile" will be in the /tmp directory when the script is run.

13-symbolic_link: Creates a symbolic link to /bin/ls, named __ls__ in the current working directory.

14-copy_html: Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

100-lets_move: Moves all files beginning with an uppercase letter to the directory /tmp/u.

101-clean_emacs: Deletes all files in the current working directory that end with the character ~.

102-tree: Creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces in your script, not more.

103-commas - Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/) Files and directories starting with a dot (.) should be listed The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning Only digits and letters are used to sort; Digits should come first. All files will have at least one letter or one digit and the listing ends with a new line.

School.mgc: Used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.



