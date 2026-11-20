# Introduction

This is the level 12 of Overthewire labs to pratice my skills.

## Challenge
[Bandit-Level 12 --> Level 13](https://overthewire.org/wargames/bandit/bandit13.html)



## What I do in this level?
- I use this comand line to get in the server.
 ````bash
 ssh -p 2220 bandit12@bandit.labs.overthewire.org
 ````

- `mktemp -d hardirname`
- `mktemp -d freferfre`
- `mktemp -d 324dewfewf3`
- `tmpdir=$(mktemp -d)`
- `trap 'ls "$tmpdir"'`
- `trap 'ls "$tmpdir"' exit`
- `mktemp -d`
- `cp data.txt /tmp/tmp.Ez2mbAFFsI | mv /tmp/tmp.Ez2mbAFFsI/data.txt newdata.txt`
- `cp data.txt /tmp/tmp.Ez2mbAFFsI | mv data.txt newdata.txt`
- `ls /tmp/tmp.Ez2mbAFFsI`
- `mv /tmp/tmp.Ez2mbAFFsI/data.txt /tmp/tmp.Ez2mbAFFsI/newdata.txt`
- `ls /tmp/tmp.Ez2mbAFFsI`
- `cat /tmp/tmp.Ez2mbAFFsI/newdata.txt`
- `hexdump -v newdata.txt`
- `hexdump -v /tmp/tmp.Ez2mbAFFsI/newdata.txt`
- `hexdump -c /tmp/tmp.Ez2mbAFFsI/newdata.txt`
- `hexdump -C /tmp/tmp.Ez2mbAFFsI/newdata.txt`
- `hexdump -C /tmp/tmp.Ez2mbAFFsI/newdata.txt | uniq -c`
- `hexdump -C /tmp/tmp.Ez2mbAFFsI/newdata.txt | sort`
- `hexdump -e '16/1 "%_u "' /tmp/tmp.Ez2mbAFFsI/newdata.txt`
- `gzip -c /tmp/tmp.Ez2mbAFFsI/newdata.txt > /tmp/tmp.Ez2mbAFFsI/output.txt`
- `cat /tmp/tmp.Ez2mbAFFsI/output.txt`
- `strings /tmp/tmp.Ez2mbAFFsI/output.txt | cat /tmp/tmp.Ez2mbAFFsI/output.txt`
- `cat /tmp/tmp.Ez2mbAFFsI/output.txt`
- `strings /tmp/tmp.Ez2mbAFFsI/output.txt | uniq -c`
- `base64 /tmp/tmp.Ez2mbAFFsI/output.txt | uniq -c`
- `base64 -d /tmp/tmp.Ez2mbAFFsI/output.txt | uniq -c`
- `base64 -d  /tmp/tmp.Ez2mbAFFsI/output.txt | uniq -c`
- `base64 /tmp/tmp.Ez2mbAFFsI/output.txt | uniq -c`
- `base64 /tmp/tmp.Ez2mbAFFsI/output.txt | sort`
- `base64 /tmp/tmp.Ez2mbAFFsI/output.txt | sort -u /tmp/tmp.Ez2mbAFFsI/output.txt`
- `sort`
- `cat data-txt | sort -u`
- `cat data.txt | sort -u`
- `base64 /tmp/tmp.Ez2mbAFFsI/output.txt | sort -u /tmp/tmp.Ez2mbAFFsI/output.txt`
- `xxd -r /tmp/tmp.Ez2mbAFFsI/output.txt > dump`
- `cd /tmp/tmp.Ez2mbAFFsI/output.txt`
- `cd /tmp/tmp.Ez2mbAFFsI`
- `xxd -r output.txt > dump`
- `file dump`
- `ls -l`
- `head newdata.txt`
- `rm output.txt dump`
- `xxd -r newdata.txt dump`
- `file dump`
- `mv dump dump.gz`
- `gzip -c dump.gz`
- `gzip -d dump.gz`
- `mv dump dump.gz`
- `gzip -d dump.gz`
- `file dump`
- `gzip -d dump.gz`
- `rm dump-gz`
- `rm dump.gz`
- `xxd -r newdata.txt dump`
- `file dump`
- `mv dump dump.gz`
- `gzip -d dump.gz`
- `cat dump`
- `file dump`
- `mv dump dump.gz2`
- `bzip2 -d dump.bz2`
- `bzip2 -d dump.bz2`
- `bzip -d dump.bz2`
- `bzip2 -d dump.bz2`
- `mv dump dump.bz2`
- `mv dump.gz2 dump.bz2`
- `bzip2 -d dump.bz2`
- `file dump`
- `mv dump dump.gz`
- `gzip -d dump.gz`
- `file dump`
- `mv dump dump.tar`
- `tar -xf dump.tar`
- `file data5.bin`
- `tar -xf data5.bin`
- `file data6.bin`
- `mv data6.bin data6.bz2`
- `bzip2 -d data6.bz2`
- `file data6`
- `tar -xf data`
- `cat data6`
- `file data6`
- `tar -xf data6`
- `file data8.bin`
- `mv data8.bin data8.gz`
- `gzip data9.gz`
- `gzip -d data9.gz`
- `gzip -d data8.gz`
- `file data8.gz`
- `file data8`
- `cat data8`

## What I learn in that level of bandit?
- I learn how hard and meaning is descompress a file a lot of times, and how the compress files comands work.