- 0-iam_betty is a script that switches the current user to the user `betty`.

- 1-who_am_i is a script that prints the effective username of the current user.

- 2-groups is a script that prints all the groups the current user is part of.

- 3-new_owner is a script that changes the owner of the file `hello` to the user `betty`.

- 4-empty is a script that creates an empty file called `hello`.

- 5-execute is a script that adds execute permission to the owner of the file hello.

- 6-multiple_permissions is a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

- 7-everybody is a script that adds execution permission to the owner, the group owner and the other users, to the file hello.

- 8-James_Bond is a script that sets the permission to the file hello as follows:
  - Owner: no permission at all
  - Group: no permission at all
  - Other users: all the permissions

- 9-John_Doe is a script that sets the mode of the file hello to this:
```
	-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```

- 10-mirror_permissions is a script that sets the mode of the file hello the same as olleh’s mode.

- 11-directories_permissions is a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

- 13-change_group is a script that changes the group owner to `school` for the file `hello`.

- 100-change_owner_and_group is a script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

- 101-symbolic_link_permissions is a script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.

- 102-if_only is a script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

- 103-Star_Wars is a script that will play the StarWars IV episode in the terminal.
