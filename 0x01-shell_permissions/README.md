## Description of each script I wrote for 0x01-shell_permission tasks

0. su betty script that changes user ID to betty and uses exactly 8 characters
and assumes that the user betty exists

1. whoami script that shows current users user id. id -un also works

2. groups script that prints all groups that the current user is in id -Gn
also works

3. chown betty hello script that changes owner of the file hello to betty

4. touch hello script that creates empty file named hello

5. chmod u+x hello script that adds execution permission to the owner of
the file hello

6. chmod ug+x,o+r hello script that adds execute permission to the owner
and group owner and read permission to the other users in regards to the file hello

7. chmod ugo+x hello script that adds execute permission to the owner, group owner, and 
to the other users in regards to the file hello. no commas used

8. chmod 007 hello script that sets no permission to owner and group owner and all the
permissions to the other users... Mayhem

9. chmod 753 hello script that sets the mode of the file hello to -rwxr-x-wx

10. chmod --reference=olleh hello script that sets the mode of the file hello the same as
olleh's mode

11. chmod -R +X . script adds execute permision to all subdirectories of the current
directory for the owner, the group owner, and all other users

12. mkdir -m 751 dir_holberton script that creates a directory called dir_holberton
with permissions 751 in current working directory

13. chgrp holberton hello script changes the group owner to holberton for the file hello

14. chown betty:holberton * script changes owner to betty and group owner to holberton
for all files and directories in working directory

15. chown -h betty:holberton _hello script changes the owner to betty and group owner 
to holberton of symbolic link file _hello

16. chown --from=guillaume betty hello script that changes the owner of the file hello
to betty only if it is owned by the user guillaume

17. telnet towel.blinkenlights.nl script that plays Star Wars IV in the terminal

18. Create a man page for holberton as specified in the task. Key notes:

- every man page starts with its title .TH where you can specify the title, date, etc.

- you should have a name, synopsis, description, options, see also, bugs, author sections

- you can markup your text with .TH, .B, .I, .SH amongst others     
 
