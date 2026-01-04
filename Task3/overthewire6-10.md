# Over The Wire

## Bandit 6-7

### Goal:
To find the password for the next level that is stored somewhere on the server and has all of the following properties:
owned by user bandit7
owned by group bandit6
33 bytes in size



### steps:

Connect to the wargame via SSH (use the password from the previous level).

Find the file owned by user bandit7,
owned by group bandit6, 33 bytes in size

Displays the password in the file.



### Commands used:

1. ssh bandit6@bandit.labs.overthewire.org -p 2220
2. find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
3. cat 
4. exit-d

**Password:**
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

## Bandit 7-8

### Goal:
To find the password for the next level that is stored in the file data.txt next to word millionth



### steps:

Connect to the wargame via SSH (use the password from the previous level).

Open the file data.txt next to word millionth

Displays the password in the file.



### Commands used:

1. ssh bandit7@bandit.labs.overthewire.org -p 2220
2. grep millionth data.txt
3. exit -d

**Password:**
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

## Bandit 8-9

### Goal:
To find the password for the next level that is stored in the file data.txt and is the only line of texts that occurs only once



### steps:

Connect to the wargame via SSH (use the password from the previous level).

Find the text line that only occurs once in the file data.txt

Displays the password in the file.



### Commands used:

1. ssh bandit7@bandit.labs.overthewire.org -p 2220
2. sort data.txt | uniq -u
3. exit -d

**Password:**
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

## Bandit 9-10

### Goal:
To find the password for the next level that is stored in the file data.txt in one of the few human-readable strings, preceded by several '='characters.



### steps:

Connect to the wargame via SSH (use the password from the previous level).

Find the text that is human-readable string preceded by several '='characters

Displays the password in the file.



### Commands used:

1. ssh bandit7@bandit.labs.overthewire.org -p 2220
2. strings data.txt | grep '=='
3. exit -d

**Password:**
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

## Bandit 10-11

### Goal:
To find the password for the next level that is stored in the file data.txt which contains base64 encoded data

### steps:

Connect to the wargame via SSH (use the password from the previous level).

Find the text in data.txt and decode it 

Displays the password in the file.



### Commands used:

1. ssh bandit7@bandit.labs.overthewire.org -p 2220
2. ls
3. cat data.txt | base64 -d
4. exit -d

**Password:**
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr









