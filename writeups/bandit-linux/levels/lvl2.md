# Introduction

This is the level 2 of Overthewire labs to pratice my skills.

## Challenge
[Bandit-Level 2 --> Level 3](https://overthewire.org/wargames/bandit/bandit3.html)



## What I do in this level?
- I use this comand line to get in the server.
 ````bash
 ssh -p 2220 bandit2@bandit.labs.overthewire.org
 ````
- I found a file with special characters and I tried to see with `'filename'` but doesn't work, so I search how to see the content in that file.
- I use claude to help me to know what commands can show the hidden characters in filename, then i found `ls -b` that show the special characters in an file.
- So i found the password for the next level and store that in a .env file.


## What I learn in that level of bandit?
- Using `ls -b` show the speacial characters in a file.
- `./--` is helpful in situations like that, beacuse if I type only cat --..., it will asign that I'm trying to use help commands.
- An shortcut to this method, `cat ./[first characters of the file]` and click TAB, with will complete the filename