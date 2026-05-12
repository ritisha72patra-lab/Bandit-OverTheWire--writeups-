# Solution to level 10->11
We commence with logging into the game through ssh with the help of the command: ssh bandit10@bandit.labs.overthewire.org -p 2220

The password for this was the password obtained in the previous level.
## Methodology
To obtain the password from this kind of decoded text, we write the command in this format : *type -d filename* where -d stands for decode and the filename should be written with extension.

So the command for this level is *base64 -d data.txt* and we get the password for the next level displayed.

Refer to the screenshots for more details.
