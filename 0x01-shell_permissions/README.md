Task for the projects Shell Permissions

Exercise 0: Create a script that switches the current user to the 
user betty: su betty.

Exercise 1: Write a script that prints the effective username of 
the current user: whoami.

Exercise 2: Write a script that prints all the groups the current 
user is part of: groups.

Exercise 3: Write a script that changes the owner of the file hello 
to the user betty: sudo chown betty hello.

Exercise 4: Write a script that creates an empty file called hello:
touch hello.

Exercise 5: Write a script that adds execute permission to the owner 
of the file hello: sudo chmod u+x hello.

Exercise 6: Write a script that adds execute permission to the owner 
and the group owner, and read permission to other users, to the file 
hello: chmod ug+x, o+r hello

Exercise 7: Write a script that adds execution permission to the owner,
the group owner and the other users, to the file hello: chmod 111 hello

Exercise 8: Write a script that sets permissions to the file hello users
all the permissions: chmod 007

Exercise 9: Write a script that sets the mode of the file hello to this
-rwxr-x-wx: chmod 753 hello

Exercise 10: Write a script that sets the mode of the file hello the
same as olleh's mode: chmod --reference=olleh's hello.

Exercise 11: Create a script that adds execute permission to all 
subdirectories of the current directory for the owner, group owner and
all other users: chmod -R a+X .

Exercise 12: Create a script that creates a directory called my_dir with
permissions 751 in the working directory: mkdir -m751 my_dir

Exercise 13: Write a script that changes the group owner to school for the
file hello: sudo chgrp school hello.

Exercise 14: Write a script that changes the owner to vincent and the 
group owner to staff for all the files and directories in the working 
directory: sudo chown vincent:staff *.

Exercise 15: Write a script that changes the owner and the group owner
 of _hello to vincent and staff respectively: sudo chown -h vincent:staff _hello

Exercise 16: Write a script that changes the owner of the file hello to 
vincent only if it is owned by the user guillaume: sudo chown --from=guillaume vincent hello 

Exercise 17:telnet towel.blinkenlights.nl
