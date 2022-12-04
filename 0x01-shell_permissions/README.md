#THIS IS MY README FILE FOR SHELL_PERMISSIONS PROJECT#
This task talks about how to give permissions to the owner, group and other users of files and directories to read(r), write(w), execute(x) the files and directories either by entering the office of a superuser(su), or by doing the work of a superuser without entering the office or environment (using sudo before command.
These are the tasks done under this project:
1) Create a script that switches the current user to the user "betty". >> su betty
2) Write a script that print the effective username of the current user. >> id -un
3) Write a script that prints all the groups the current user is part of. >> groups or id -Gn
4) Write a script that changes the owner of a file 'hello' the user 'betty". >> chown betty hello
5) Write a script that creates an empty file called 'hello'. >> touch hello
6) Write a script that add execute permission to the owner of the file 'hello'. >> chmod u+x hello
7) Write a script that add execute permission to the owner and ther group owner, and read permission to other users, to the file 'hello'. >> chmod uo+x, o+r hello
8) Write a script that adds execution permission to the owner, the group owner and the other users, to the file 'hello'. chmod ugo+x hello or chmod a+x or chmod +x hello
9) Write a script that set the permission to the file 'hello' as follows:
~Owner: no permission at all
~Group: no permission at all
~Other users: all the permissions >> chmod 007 hello
10) Write a script that sets the mode of the file 'hello' to this:
~ -rwx-x-wx ~ >> chmod 753 hello
11) Write a script that set the mode of the file 'hello' the same as 'olleh's' mode. >> sudo chmod --reference=olleh hello
12) Create a script that add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed. >> chmod -R +x . or chmod -R ugo+x . or chmod a+x .
13) Create a script that creates a directory called my_dir with permission 751 in the working directory. >> mkdir -m 751 my_dir
14) Write a script that changes the group owner to school for the file 'hello' >> chgrp school hello
15) Write a script that changes the owner to 'vincent' and the group owner to 'staff' for all the files and directories in the working directory. >> chown vincent:staff *
16) Write a script that changes the owner and the group owner of '_hello' to 'vincent' and 'staff' respectively. >> chown -h vincent:staff _hello
17) Write a script that changes the owner of the file 'hello' to 'betty' only if it is owned by the user 'guillaume'. >> chown --from=guillaume betty hello
18) Write a script that will play the StarWars IV in the terminal. >> telnet towel.blinkenlights.nl
