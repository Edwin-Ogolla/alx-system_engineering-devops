Shell permissions exercise
0-iam_betty - This script changes user to "betty
1-who_am_i -This script prints effective user name of the current user
2-groups- This script prints all the groups the current user is part of
3-new_owner - This script changes the owner of file "hello" to user "betty"
4-empty - This script creates an empty file called "hello"
5-execute - This script adds execute permission to the owner of the file "hello"
"6-multiple_permissions" - This script adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello"
7-everybody - This script adds execution permission to the owner, the group owner and the other users, to the file "hello"
8-James_Bond - This script sets the permission to the file hello as follows:

		Owner: no permission at all
		Group: no permission at all
		Other users: all the permissions
9-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 7539-John_Doe - This script sets mode of "hello" to 753
10-mirror_permissions - This script sets the mode of the file hello the same as olleh’s mode.
11-directories_permissions - This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12-directory_permissions - This script creates a directory called my_dir with permissions 751 in the working directory.
13-change_group - This script changes the group owner to school for the file hello
100-change_owner_and_group - This script changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
101-symbolic_link_permissions - This script changes the owner and the group owner of _hello to vincent and staff respectively
102-if_only - This script changes the owner of the file hello to betty only if it is owned by the user guillaume
