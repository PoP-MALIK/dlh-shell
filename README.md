# dlh-shell

Holberton School project covering Linux permissions and shell scripting.

## permissions

- `0-iam_betty`: Script that switches the current user to the user `betty`.
- `1-who_am_i`: Script that prints the effective username of the current user.
- `2-groups`: Script that prints all the groups the current user is part of.
- `3-new_owner`: Script that changes the owner of the file `hello` to the user `betty`.
- `4-empty`: Script that creates an empty file called `hello`.
- `5-execute`: Script that adds execute permission to the owner of the file `hello`.
- `6-multiple_permissions`: Script that adds execute permission to the owner and group, and read permission to others, for the file `hello`.
- `7-everybody`: Script that adds execute permission to the owner, group, and other users for the file `hello`.
- `8-James_Bond`: Script that sets permissions on `hello` to 007 (owner: none, group: none, other: rwx).
- `9-John_Doe`: Script that sets the mode of `hello` to 753 (rwxr-x-wx).
- `10-mirror_permissions`: Script that copies the mode of `olleh` onto `hello`.
- `11-directories_permissions`: Script that adds execute permission to all subdirectories for owner, group, and other.
- `12-directory_permissions`: Script that creates a directory `my_dir` with permissions 751.
- `13-change_group`: Script that changes the group owner of `hello` to `school`.
- `14-change_owner_and_group`: Script that changes owner to `vincent` and group to `staff` for everything in the working directory.
- `15-symbolic_link_permissions`: Script that changes owner and group of the symbolic link `_hello` to `vincent` and `staff`.
- `16-if_only`: Script that changes the owner of `hello` to `vincent` only if currently owned by `guillaume`.
