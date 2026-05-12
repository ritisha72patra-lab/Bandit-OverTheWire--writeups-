# Solution to level 1 -> 2
We commence with logging into the game through ssh using the command : ssh bandit1@bandit.labs.overthewire.org -p 2220

The password for this level was obtained from the previous level.

## Methodology
We initially use the ls command to get the file '-' but the contents of this can't be accessed by just using cat -

Hence we use an alternative command, cat ./- to access the password.
