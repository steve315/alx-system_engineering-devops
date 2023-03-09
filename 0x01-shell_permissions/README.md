# Project :0x01-shell_permissions
## Bash Scripts

* 0-iam_betty : switches the current user to betty
1-who_am_i - prints the effective username of the current user
* 2-groups - prints all groups the user is currently part of
* 3-new_owner - changes the owner of file hello to the user betty
* 4-empty - creates an empty file called hello
* 5-execute - adds executive permissions to the own of the file hello
* 6-multiple_permissions - adds execute permission to the owner and the group owne	r, and read permission to other users, to the file hello
* 7-everybody - addsnexecution permission to u, g and o to the file hello
* 8-James_Bond - sets permission for hello u = 0, g = 0, o = 7
* 9-John_Doe - sets the mode of the file hello too -rwxr-x-wx
* 10-mirror_permissions - sets the mode of the file hello the same as olleh’s mod	e.
* 11-directories_permissions - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
* 100-change_owner_and_group - changes owner to vincent and group to staff for all files and directories in the working directory
* 101-symbolic_link_permissions - changes the owner and group of symlink(hello) to vincent and staff respectfully
* 102-if_only - changes ownership of file hello to betty only if owner=guillaume
* 103-Star_Wars - plays the StarWars IV episode in the terminal
