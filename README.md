# bandit-wargame
Repo for the challenge files in the Bandit Wargame

## Link
https://overthewire.org/wargames/bandit/


## Levels

### Level 0

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
## passwrod: bandit0
```

### Level 0-1

```bash
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme 
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

bandit0@bandit:~$ 
```

### Level 1-2

```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
bandit1@bandit:~$ cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

### Level 2-3
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
bandit2@bandit:~$ cat ./--spaces\ in\ this\ filename-- 
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

### Level 3-4
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
bandit3@bandit:~$ cat inhere/...Hiding-From-You 
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## Listing everything, even hidden files
bandit3@bandit:~/inhere$ ls -a
.  ..  ...Hiding-From-You
```

### Level 4-5
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
cd inhere/
bandit4@bandit:~/inhere$ file ./-*
./-file00: Non-ISO extended-ASCII text, with no line terminators, with overstriking
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
bandit4@bandit:~/inhere$ cat ./-file07
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```


