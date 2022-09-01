0-iam_betty:	Switches the current user to betty

1-who_am_i:	Prints the username of the current user (Leart command whoami. Went with echo $USER) #rebel. I was wrong

2-groups:	Prints all the groups the user is a part of

3-new_ower: Changes owner of the file 'hello' to the user betty. (Noted that chown should always be preceeded by sudo)

4-empty: Creates an empty file called hello

5-execute: Adds execute permission to the owner of the file hello

6-multiple_permissions:	Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

7-everybody:	Adds execute permission to everyone for the file hello

8-James_Bond:	Sets permission 007 to the file hello

9-John_Doe:	Sets permission 753 to the file hello

10-mirror_permissions:	Sets mode of the file hello to the same as file olleh

11-directories_permissions:	Adds execute permissions for everyone to the subdirectories of the current folder (Done by capitalizing, (+/-)RWX)

12-directory_permissions:	Creates a directory 'my_dir' with permissions 751 set

13-change_group:	Changes group owner to 'school' for file 'hello'

100-change_owner_and_group:	Changes owner to vincent and the group owner to staff for all files and directories in the working directory (chown user:group file)

101-symbolic_link_permissions:	Changes owner of symbolic link '\_hello' to vincent and staff respectively

102-if_only:	Changes the owner of the file 'hello' to 'betty' only if it is owned by the user 'guillaume' (chown --from:guillame betty hello)

103-Star_Wars:	Plays StarWars IV episode in the terminal
