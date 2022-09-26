0-iam_betty switches users
1-who_am_i displays the current user's name
2-groups prints all the groups of the current user
3-new_owner changes the owner of a file
4-empty creates an empty file
5-execute adds execute permission to the owner of the file hello
6-multiple_permissions adds execute permission to the owner and the group owner, and read permission to other users
7-everybody adds execution permission to the owner, the gorup owner and the other users
8-James_Bond sets specific permissions : no permissions for the owner and group, other users = all permissions
9-John_Doe sets specific permissions : -rwxr-x-wx
10-mirror_permissions sets the mode of the file hello the same as olleh's mode
11-directories_permissions adds execute permissions to all subdirectories of the current directory for the owner, the group owner and other users
12-directory_permissions creates a directory called my_dir with permissions 751 in the current directory
13-change_group changes the group owner to school for the file hello
14-change_owner_and_group changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
15-symbolic_link_permissions changes the owner and the group owner of _hello to vincent and staff respectively
16-if_only changes the owner of the file hello to vincent only if it is owned by the user guillaume
