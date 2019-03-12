CHMOD

chmod is used to change the permissions of files or directories.

In general, chmod commands take the form:

chmod [options]...permissions ...file name

If no options are specified, chmod modifies the permissions of the file specified by file name to the permissions specified by permissions.

permissions defines the permissions for the owner of the file (the "user"), members of the group who owns the file (the "group"), and anyone else ("others"). There are two ways to represent these permissions: with symbols (alphanumeric characters), or with octal numbers (the digits 0 through 7).

The digits are interpreted as follows:
4 stands for "read",
2 stands for "write",
1 stands for "execute", and
0 stands for "no permission."

So 7 is the combination of permissions 4+2+1 (read, write, and execute), 5 is 4+0+1 (read, no write, and execute), and 4 is 4+0+0 (read, no write, and no execute)