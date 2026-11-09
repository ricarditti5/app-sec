# Introduction

This is the level 6 of Overthewire labs to pratice my skills.

## Challenge
[Bandit-Level 6 --> Level 7](https://overthewire.org/wargames/bandit/bandit7.html)



## What I do in this level?
- I use this comand line to get in the server.
 ````bash
 ssh -p 2220 bandit6@bandit.labs.overthewire.org
 ````
- Again I use the find with some conditions to find the file, but something interesting happen, i see a lot of files that require permission.
- `find / -user bandit7 -group bandit6 -size 33c`

## What I learn in that level of bandit?
- I learn that I canot access all the files in a server without permition, even when I put the password.
