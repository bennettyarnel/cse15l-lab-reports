![image](Ex12.png)

cd:
1) CD with no arguments: Running CD with no arguments returns you to the home directory from whatever directory you are currently in. If you are in the home directory already, you just won't go anywhere.
2) CD with directory path: The change directory command with a directory path will take you to the new directory you put in the command line. That is the point of the change directory command.
3) Because the change directory command is meant for directories / folders and not files, running the command with a path to a file will result in the default error message "No such file or directory." CD is a valid command only for directories.

ls:
1) The ls or list command shows information about various files or directories, depending on where you currently are in your environment. In the case of just ls with no arguements, the contents of the current directory will be displayed, in this case lecture1. If messages was not a subdirectory of lecture1 it would display both directories but because lecture1 is the only directory in the home directory that is all that is displayed when running ls with no arguements
2) ls lecture1 lists the contents of the lecture1 directory, including messages which is also a directory it is just inside the lecture1 directory.
3) Running ls with a path to a text file just displays the path to the text file because the purpose of ls is to display the contents of directories so when given a file path the command will just display that file, not it's contents. 

![image](Ex3.png)


