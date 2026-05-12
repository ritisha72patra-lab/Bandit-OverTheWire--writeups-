# Solution to level 4 -> 5
We commence with logging into the game through ssh using the command: ssh bandit4@bandit.labs.overthewire.org -p 2220

The password was obtained from the previous level.

## Methodology
First we change the directory to the inhere directory using the cd command.

To access the type of file present in Linux, we use the 'file' command. The command 'file *' should be giving us all the types but in this case, we are getting an error stating no file found as the file name might have spaces.

To deal with such an issue, we alter the command to 'file ./-file*' , which gives us all the types. Further we use the 'cat' command to access the contents of that file.

Refer to the screenshots for more details.
