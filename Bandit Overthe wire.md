#Bandit level 0 - 1:

##Goal:
Find the file called readme located in home directory to find the password for next level.



##steps :

Connect using SSH to the wargame.

Find the filename called "readme".

Display the password in the file.



##Commands used:

1. ssh bandit0@bandit.labs.overthewire.org -p 2220
2. ls
3. cat readme
4. exit



#Bandit level 1-2:

##Goal:
To find the password for the next level, which is stored in a file called - located in the home directory.



##steps:

Connect to the wargame via SSH (use the password from the previous level).

Find the filename -.

Display the password in the file.



##Commands used:

1. ssh bandit1@bandit.labs.overthewire.org -p 2220
2. ls
3. cat ./-
4. exit



#Bandit level 2-3:

##Goal:
To find the password for the next level, which is stored in a file called --spaces in this filename-- located in the home directory.



##steps:

Connect to the wargame via SSH (use the password from the previous level).

Find the filename --spaces in this filename--.

Display the password in the file.



##Commands used:

1. ssh bandit2@bandit.labs.overthewire.org -p 2220
2. ls
3. cat "./--spaces in this filename--"
4. exit



#Bandit level 3-4:

##Goal:
To find the password for the next level, which is stored in a hidden file in the inhere directory



##steps:

Connect to the wargame via SSH (use the password from the previous level).

Change directory to inhere.

Find the hidden file.

Display the password in the file.



##Commands used:

1. ssh bandit3@bandit.labs.overthewire.org -p 2220
2. ls
3. cd inhere
4. ls -la
5. cat ..Hiding-From-You
6. exit



#Bandit level 4-5:

##Goal:
To find the password for the next level, which is stored in a only human-readable file in the inhere directory



##steps:

Connect to the wargame via SSH (use the password from the previous level).

Change directory to inhere.

Find the file with ASCII text.

Display the password in the file.



##Commands used:

1. ssh bandit4@bandit.labs.overthewire.org -p 2220
2. ls
3. cd inhere
4. ls
5. file ./\*
6. cat ./-file07
7. exit



#Bandit level 5-6:

##Goal:
To find the password for the next level, which is stored in a file in the inhere directory
which is human-readable, 1033 bytes in size, and not executable.



##steps:

Connect to the wargame via SSH (use the password from the previous level).

Change directory to inhere.

Find the human-readable file, 1033 bytes in size, and not executable.

Display the password in the file.



##Commands used:

1. ssh bandit5@bandit.labs.overthewire.org -p 2220
2. ls
3. cd inhere
4. find . -type f -size 1033c ! -executable
5. cat ./maybehere07/.file2
6. exit
