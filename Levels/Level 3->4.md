# Solution to level 3 -> 4
We commence with logging into the game through ssh using the command: ssh bandit3@bandit.labs.overthewire.org -p 2220

The password was obtained from the previous level.

# Methodology
To obtain the hidden directories, we use the command ls -a.

Further we shift into the inhere directory using cd or change directory and further use ls -a to access the files.

cat command is used to access the contents of the file ...Hiding-From-You, which consists of the required password.
