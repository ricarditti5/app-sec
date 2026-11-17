# Introduction

This is the level 9 of Overthewire labs to pratice my skills.

## Challenge
[Bandit-Level 9 --> Level 10](https://overthewire.org/wargames/bandit/bandit10.html)



## What I do in this level?
- I use this comand line to get in the server.
 ````bash
 ssh -p 2220 bandit9@bandit.labs.overthewire.org
 ````
- `strings data.txt | uniq -c`

## What I learn in that level of bandit?
- I was looking for a method to see how to see binary data, and I discovery that the normal cat It is enough to solve this, but I wanted to understand why that string I found is the password
- So i search how to see binary data with grep, and discover if I use the `strings` command I'll turn binary into string, and I pip with `uniq -c` to see if some secret will apeer
- And I found the ==== statment guiding me to the secret I was looking for.