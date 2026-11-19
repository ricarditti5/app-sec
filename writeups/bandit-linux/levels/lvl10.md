# Introduction

This is the level 10 of Overthewire labs to pratice my skills.

## Challenge
[Bandit-Level 10 --> Level 11](https://overthewire.org/wargames/bandit/bandit11.html)



## What I do in this level?
- I use this comand line to get in the server.
 ````bash
 ssh -p 2220 bandit10@bandit.labs.overthewire.org
 ````
- `base64 -d data.txt`

## What I learn in that level of bandit?
- I learn what base64 command do and the utility, and I found a flag that help me to descover and learn that only using `base64 file` just show a few binary data, but if I use `-d` flag that show the real data inside the file.