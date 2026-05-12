# Solution to level 6->7
We commence with logging into the game through ssh with the help of the command: ssh bandit6@bandit.labs.overthewire.org -p 2220

The password for this was the password obtained in the previous level.
## Methodology
We use the 'find' command as before and include parameters like '-user' and '-group' to define the find the file sccordingly.

When we run the command *find / -user bandit7 -group bandit6 -size 66c*, we get all the files, but most of them have the permission denied.

We search for the one file that we are permitted to access and that contains the password for the next level.
