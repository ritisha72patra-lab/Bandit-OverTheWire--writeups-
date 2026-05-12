# Solution to level 8->9
We commence with logging into the game through ssh with the help of the command: ssh bandit8@bandit.labs.overthewire.org -p 2220

The password for this was the password obtained in the previous level.
## Methodology
To obtain the only line of text that occurs only once, we use two commands, sort and uniq.

'sort' is used first to sort all the text given in aphabetical order, after which 'uniq' is used to remove the duplicates. In this case, uniq is followed by the parameter '-u', which prints the only line of text that occurs uniquely.

So the final command is *sort data.txt | uniq -u*. This gives us the password for the nest level.

Refer to the screenshots for more details
