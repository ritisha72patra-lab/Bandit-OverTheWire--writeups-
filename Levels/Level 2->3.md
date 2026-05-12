# Solution to level 2 -> 3
We commence with logging into the game through ssh suing the command : ssh bandit2@bandit.labs.overthewire.org -p 2220

The password for this was obtained in the previous level.

# Methodology
We use the ls command to obtain the different files and directories. This required file cannot be accessed just by using the cat command as the it contains '--' and spaces.

To access this we use another alternative way :  *cat -- '--spaces in this filename--'* to obtain the password
