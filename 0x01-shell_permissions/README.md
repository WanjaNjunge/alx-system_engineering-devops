This contains scripts for linux permissions
Create a script that switches the current user to the user betty, su betty
a script that prints the effective username of the current user, id -un
a script that prints all the groups the current user is part of
a script that changes the owner of the file hello to the user betty, chown betty hello
a script that creates an empty file called hello, touch hello
a script that adds execute permission to the owner of the file hello, chmod u+x hello
a script that adds execution permission to the owner, the group owner and the other users, to the file hello, chmod ugo+ hello
a script that sets the permission to the file hello, chmod 007 hello
chmod 753 hello for task 9
a script that sets the mode of the file hello the same as olleh’s mode, chmod --reference=olleh hello
