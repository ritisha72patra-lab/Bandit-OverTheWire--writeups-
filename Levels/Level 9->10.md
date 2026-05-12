# Solution to level 9->10
We commence with logging into the game through ssh with the help of the command: ssh bandit9@bandit.labs.overthewire.org -p 2220

The password for this was the password obtained in the previous level.
## Methodology
As we need to obtain human-readable strings, we begin with the 'strings' command followed by the file. Further to access the contents following several '=', we use the grep command.

The command is 'strings data.txt | grep "==*"'. We mention 2 '=' as it was mentioned in the question to track several '=', where 2 in the minimum.

Refer to the screenshots for more details.
