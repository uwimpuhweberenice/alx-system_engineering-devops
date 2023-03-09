0x01. Shell, permissions\
\
0: switches the current user to the user betty\
1: prints the effective username of the current user\
2: prints all the groups the current user is part of\
3: changes the owner of the file hello to the user betty\
4: creates an empty file called hello\
5: adds execute permission to the owner of the file hello\
6: adds execute permission to the owner and the group owner, and read permission to other users, to the file hello\
7: adds execution permission to the owner, the group owner and the other users, to the file hello\
8: sets the permission to the file hello as follows:\
	&emsp;Owner: no permission at all\
	&emsp;Group: no permission at all\
	&emsp;Other users: all the permissions\
9: sets the mode of the file hello to this:\
	&emsp;-rwxr-x-wx\
10: sets the mode of the file hello the same as olleh’s mode\
11: adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users\
12: creates a directory called my_dir with permissions 751 in the working directory\
13: changes the group owner to school for the file hello\
100: changes the owner to vincent and the group owner to staff for all the files and directories in the working directory\
101:  changes the owner and the group owner of _hello to vincent and staff respectively where _hello is a symbolic link\
102: changes the owner of the file hello to betty only if it is owned by the user guillaume\
103: will play the StarWars IV episode in the terminal
