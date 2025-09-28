# THE ROOT
In this challenge, to get the flag, we must invoke a program by providing its path on the command line. 

## MY SOLVE
**FLAG:** `pwn.college{sf5n7zd1S65D_oAwU7O3pPiHnLS.QX4cTO0wyN1EzNzEzW}` 

For this challenge, I first understood that filesystem starts at /. Under that there are directories,configuration files, programs and flags. In this challenge, we needed to invokde a pre-existing program by
providing a path /pwn .  This style of path, one that starts with the root directory, is referred to as an "absolute path". I ran that and got the flag.

```
hacker@paths~the-root:~$ /pwn
BOOM!!!
Here is your flag:
pwn.college{sf5n7zd1S65D_oAwU7O3pPiHnLS.QX4cTO0wyN1EzNzEzW}
```

## WHAT I LEARNED
Through this challenge, I learnt that filesystem starts at / and to invoke a program, I must provide a path.

## REFERENCES
Did not use any references.

