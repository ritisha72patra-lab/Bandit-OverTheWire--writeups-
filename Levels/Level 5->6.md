# Solution to level 5 -> 6
We commence with logging into the game through ssh with the help of the command: ssh bandit5@bandit.labs.overthewire.org -p 2220

The password for this was the password obtained in the previous level.
## Methodology
The first step as usual is to change our directory to the inhere directory as mentioned using the cd command.

To find a file of that format, we use the 'find' command along with the size parameter, which in this case is 1033 bytes.

The command is *find -size 1033c* where c stands for bytes. Similarly for kilobytes, megabytes and gigabytes, it is k, M and G.

Once we run this command, we get a file, whose contents we can access using the 'cat' command and the password is there.
