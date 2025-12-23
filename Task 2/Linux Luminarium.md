# Linux Luminarium

## Module 1: Hello Hackers

### Challenge: Intro To Commands

**Commands Used:**

hello

**Output:**
Success! Here is your flag:
pwn.college{UM35YbHijei4H5tHAtQHI_04PEm.QX3YjM1wSO2QDM1EzW}

**Flag:**
pwn.college{UM35YbHijei4H5tHAtQHI_04PEm.QX3YjM1wSO2QDM1EzW}

### Challenge: Intro To Arguments

**Commands Used:**

echo hello

hello hackers

**Output:**
Success! Here is your flag:
pwn.college{Yj1zFFyYgfoUIol6QIa7yut8rxn.QX4YjM1wSO2QDM1EzW}

**Flag:**
pwn.college{Yj1zFFyYgfoUIol6QIa7yut8rxn.QX4YjM1wSO2QDM1EzW}

### Challenge: Command History

**Commands Used:**

history

**Output:**

    1.whoami

    2.ls

    3.ls -a

    4.cat .bash_history

    5.cat .config

    6.cd .config

    7.ls

    8.ls -a

    9.cat .

   10.cd..

   11.cd ..

   12.hello

   13.bash

   14.hello

   15.echo hello

   16.hello

   17.hello hackers

   18.the flag is pwn.college{8fryqTHW0iwYgiXSubQeKEw4bDF.0lNzEzNxwSO2QDM1EzW}

   19.history

**Flag:**
pwn.college{8fryqTHW0iwYgiXSubQeKEw4bDF.0lNzEzNxwSO2QDM1EzW}

## Module 2: Ponding Paths

### Challenge: The Root

**Commands Used:**

/pwn

**Output:**
BOOM!!!
Here is your flag:
pwn.college{sqeMfb54IGBnfoKmMe1gKWmMa3e.QX4cTO0wSO2QDM1EzW}

**Flag:**
pwn.college{sqeMfb54IGBnfoKmMe1gKWmMa3e.QX4cTO0wSO2QDM1EzW}

### Challenge: Programs and absolute path

**Commands Used:**

/challenge/run

**Output:**
Correct!!!
/challenge/run is an absolute path! Here is your flag:
pwn.college{wJEaPRlDMX0oycpmszuDWqAzoo9.QX1QTN0wSO2QDM1EzW}

**Flag:**
pwn.college{wJEaPRlDMX0oycpmszuDWqAzoo9.QX1QTN0wSO2QDM1EzW}

### Challenge: Position thy self

**Commands Used:**

/challenge/run

cd /home

/challenge/run

**Output:**
Here is your flag:
pwn.college{gy5_Tcn2Kr0GoeULhfiR5tLDZdT.QX2QTN0wSO2QDM1EzW}

**Flag:**
pwn.college{gy5_Tcn2Kr0GoeULhfiR5tLDZdT.QX2QTN0wSO2QDM1EzW}

### Challenge: Position elsewhere

**Commands Used:**

/challenge/run

cd /usr/bin

/challenge/run

cd /etc

/challenge/run

cd proc/140

/challenge/run

cd /usr/share/zoneinfo/posix/Asia

/challenge/run

cd /usr/share/doc

**Output:**
Starting level 1.
Incorrect...
You are not currently in the /usr/bin directory.
Please use the `cd` utility to change directory appropriately.

Starting level 1.
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 2
Please use the `cd` utility to change directory to /etc

Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 3
Please use the `cd` utility to change directory to /proc/140

Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 4
Please use the `cd` utility to change directory to /usr/share/zoneinfo/posix/Asia

Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Moving on to level 5
Please use the `cd` utility to change directory to /usr/share/doc

Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{QZxjc_-HzfZNQV47yCLMPwPAtYV.QX3QTN0wSO2QDM1EzW}


**Flag:**
pwn.college{QZxjc_-HzfZNQV47yCLMPwPAtYV.QX3QTN0wSO2QDM1EzW}

### Challenge: Implicit relative paths, from /

**Commands Used:**

cd /

challenge/run

**Output:**
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{kagsVHt6JQIkBA_wzVEcGVrIVCU.QX5QTN0wSO2QDM1EzW}


**Flag:**
pwn.college{kagsVHt6JQIkBA_wzVEcGVrIVCU.QX5QTN0wSO2QDM1EzW}

### Challenge: Explicit relative paths, from /

**Commands Used:**

./challenge/run

**Output:**
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{IJHX2yN8dxWT4v329qiu-8bkBOM.QXwUTN0wSO2QDM1EzW}

**Flag:**
pwn.college{IJHX2yN8dxWT4v329qiu-8bkBOM.QXwUTN0wSO2QDM1EzW}

### Challenge: Implicit relative path

**Commands Used:**
cd /challenge

./ run

**Output:**
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{M3w712SUNgydAqvJWCAOaGLqv1T.QXxUTN0wSO2QDM1EzW}

**Flag:**
pwn.college{M3w712SUNgydAqvJWCAOaGLqv1T.QXxUTN0wSO2QDM1EzW}

### Challenge: home sweet home

**Commands Used:**

 /challenge/run ~/!

**Output:**
Writing the file to /home/hacker/!!
... and reading it back to you:
pwn.college{oqoi9GB32eu0GSjGasuMy8kz6KH.QXzMDO0wSO2QDM1EzW}

**Flag:**
pwn.college{oqoi9GB32eu0GSjGasuMy8kz6KH.QXzMDO0wSO2QDM1EzW}

## Module 3: Comprehending Commands

### Challenge: cat: not the pet, but the command

**Commands Used:**

cat flag

**Output:**
pwn.college{UUDd4e0dPpEPxrNnNqgA_PLxn3r.QXxcTN0wSO2QDM1EzW}

**Flag:**
pwn.college{UUDd4e0dPpEPxrNnNqgA_PLxn3r.QXxcTN0wSO2QDM1EzW}

### Challenge: catting absolute paths

**Commands Used:**

cat /flag

**Output:**
pwn.college{EmURHuKajrUY08GrwW0LsIx1lMy.QX5ETO0wSO2QDM1EzW}

**Flag:**
pwn.college{EmURHuKajrUY08GrwW0LsIx1lMy.QX5ETO0wSO2QDM1EzW}

### Challenge: more catting practice

**Commands Used:**

cat file /lib/flag

**Output:**
cat: file: No such file or directory
pwn.college{Uo7JPFfXY2d-oof5qqmG7FM6SmS.QXwITO0wSO2QDM1EzW}

**Flag:**
pwn.college{Uo7JPFfXY2d-oof5qqmG7FM6SmS.QXwITO0wSO2QDM1EzW}

### Challenge: grepping for a needle in a haystack

**Commands Used:**

grep pwn.college /challenge/data.txt

**Output:**
pwn.college{8-wZc-WsrcxqU3w-B2t7fwqzyoP.QX3EDO0wSO2QDM1EzW}

**Flag:**
pwn.college{8-wZc-WsrcxqU3w-B2t7fwqzyoP.QX3EDO0wSO2QDM1EzW}

### Challenge: comparing files

**Commands Used:**

cd /challenge

diff  decoys_only.txt decoys_and_real.txt 

**Output:**
14a15
pwn.college{wo2Q-gxjVz6dJGSrqaE4xE2yWgi.01MwMDOxwSO2QDM1EzW}

**Flag:**
pwn.college{wo2Q-gxjVz6dJGSrqaE4xE2yWgi.01MwMDOxwSO2QDM1EzW}

### Challenge: listing files

**Commands Used:**

cd /challenge

ls

./26900-renamed-run-14423

**Output:**
29600-renamed-run-14423  DESCRIPTION.md

Yahaha, you found me! Here is your flag:
pwn.college{4u-70YesAhsw5c0OrV9PQTExWZv.QX4IDO0wSO2QDM1EzW}

**Flag:**
pwn.college{4u-70YesAhsw5c0OrV9PQTExWZv.QX4IDO0wSO2QDM1EzW}

### Challenge: touching files

**Commands Used:**

touch /tmp/pwn

touch /tmp/college

/challenge/run

**Output:**
Success! Here is your flag:
pwn.college{QS9dW4yOVjznS-hUjg-a76sgp8L.QXwMDO0wSO2QDM1EzW}

**Flag:**
pwn.college{QS9dW4yOVjznS-hUjg-a76sgp8L.QXwMDO0wSO2QDM1EzW}

### Challenge: removing files

**Commands Used:**

ls

rm delete_me

/challenge/check

**Output:**
Excellent removal. Here is your reward:
pwn.college{wjwVa7Hs-evcNuEJWF1eFYifKeL.QX2kDM1wSO2QDM1EzW}

**Flag:**
pwn.college{wjwVa7Hs-evcNuEJWF1eFYifKeL.QX2kDM1wSO2QDM1EzW}

### Challenge: moving files

**Commands Used:**

mv /flag /tmp/hack-the-planet

/challenge/check

**Output:**
Correct! Performing 'mv /flag /tmp/hack-the-planet'.
/bin/mv: cannot stat '/flag': No such file or directory

Congrats! You successfully moved the flag to /tmp/hack-the-planet! Here it is:
pwn.college{c4qqrkLnpoYSDlH4alx3ESOo-u3.0VOxEzNxwSO2QDM1EzW}

**Flag:**
pwn.college{c4qqrkLnpoYSDlH4alx3ESOo-u3.0VOxEzNxwSO2QDM1EzW}

### Challenge: copying files

**Commands Used:**

cp /flag /tmp/hack-the-planet

/challenge/check

**Output:**
Correct! Performing 'cp /flag /tmp/hack-the-planet'.

Congrats! You successfully copied the flag to /tmp/hack-the-planet! Here it is:
pwn.college{4u1RWTrhQlNhKL--IW09o9kCMTW.0lNxQTMywSO2QDM1EzW}

**Flag:**
pwn.college{4u1RWTrhQlNhKL--IW09o9kCMTW.0lNxQTMywSO2QDM1EzW}

### Challenge: hidden files

**Commands Used:**

cd /

ls -a

cat /.flag-30424586911493

**Output:**
.   .dockerenv            bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-30424586911493  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr

pwn.college{8WbwAngLh_mCGhNkzo8r0svUVuC.QXwUDO0wSO2QDM1EzW}

**Flag:**
pwn.college{8WbwAngLh_mCGhNkzo8r0svUVuC.QXwUDO0wSO2QDM1EzW}


### Challenge: An Epic Filesystem Quest

**Commands Used:**

cd /

ls -a

cat GIST

cd /usr/share/icons/ubuntu-mono-light/places/22

ls -a

cat .NOTE

cd /usr/share/emacs/26.3/etc/schema

ls -a

cat REVELATION

cd /opt/linux/linux-5.4/Documentation/devicetree/bindings/arm/npmc

ls -a

cat MESSAGE

cd /usr/lib/python3/dist-packages/sympy/algebras/tests

ls -a

cat CLUE

cd /usr/share/doc/jmol/html/fr

ls -a

cat .POINTER

cd /usr/share/racket/pkgs/htdp-lib/lang/compiled

ls -a

cat INSIGHT

ls /usr/local/lib/python3.8/dist-packages/networkx/algorithms/community/tests

cat /usr/local/lib/python3.8/dist-packages/networkx/algorithms/community/tests/README-TRAPPED

cd /usr/lib/python3/dist-packages/nose/tools

ls -a

cat INFO

**Output:**
CONGRATULATIONS! Your perseverance has paid off, and you have found the flag!
It is: pwn.college{42F3cK-6qLkdGkkjSlsa-2G_tES.QX5T0DWwSO2QDM1EzW}

**Flag:**
pwn.college{42f3cK-6qlKdGkkjSJsa-2G_tES.QX5IDO0wSO2QDM1EzW}

### Challenge: making directories

**Commands Used:**

mkdir /tmp/pwn

cd /tmp/pwn

touch college

/challenge/run

**Output:**
Success! Here is your flag:
pwn.college{UBQ-WcuuCdfkgyTS37jFYYlPxaC.QXxMDO0wSO2QDM1EzW}

**Flag:**
pwn.college{UBQ-WcuuCdfkgyTS37jFYYlPxaC.QXxMDO0wSO2QDM1EzW}

### Challenge: finding files

**Commands Used:**

find /-name flag

**Output:**
pwn.college{oloRBYFtDDBhOLEU5EJKbwC_3s9.QXyMDO0wSO2QDM1EzW}

**Flag:**
pwn.college{oloRBYFtDDBhOLEU5EJKbwC_3s9.QXyMDO0wSO2QDM1EzW}

### Challenge: linking files

**Commands Used:**

ln -s /flag not-the-flag

/challenge/catflag

**Output:**
About to read out the /home/hacker/not-the-flag file!
pwn.college{Y2onrBNhFlCIbUU7TQ7EFTVmdhY.QX5ETN1wSO2QDM1EzW}

**Flag:**
pwn.college{Y2onrBNhFlCIbUU7TQ7EFTVmdhY.QX5ETN1wSO2QDM1EzW}

## Module 4: Digesting Documentation

### Challenge: Learning From Documentation

**Commands Used:**

/challenge/challenge --giveflag

**Output:**
Correct argument! Here is your flag:
pwn.college{g7KSL4pjr6qQRNBGF0Wl3nuqUIy.QX0ITO0wSO2QDM1EzW}

**Flag:**
pwn.college{g7KSL4pjr6qQRNBGF0Wl3nuqUIy.QX0ITO0wSO2QDM1EzW}

### Challenge: Learning Complex Usage

**Commands Used:**

/challenge/challenge --printfile /flag

**Output:**
Correct argument! Here is the /flag file:
pwn.college{Q3eWbFBUkMkkJeTEDTD1Vb3nzov.QX1ITO0wSO2QDM1EzW}

**Flag:**
pwn.college{Q3eWbFBUkMkkJeTEDTD1Vb3nzov.QX1ITO0wSO2QDM1EzW}

### Challenge: Reading Manuals

**Commands Used:**

man challenge

/challenge/challenge --cxkbfn 624

**Output:**
Correct usage! Your flag: pwn.college{cxkbfn6cxvi2Z4e_O25k7-A1DqI.QX0EDO0wSO2QDM1EzW}

**Flag:**
 pwn.college{cxkbfn6cxvi2Z4e_O25k7-A1DqI.QX0EDO0wSO2QDM1EzW}

### Challenge: Searching Manuals

**Commands Used:**

man challenge (after the manual opens type / flag)

/challenge/challenge --vap

**Output:**
Initializing...
Correct usage! Your flag: pwn.college{QK1mq4Gov8Q4MFSU82IJ0qE5cT4.QX1EDO0wSO2QDM1EzW}

**Flag:**
 pwn.college{QK1mq4Gov8Q4MFSU82IJ0qE5cT4.QX1EDO0wSO2QDM1EzW}

### Challenge: Searching For Manuals

**Commands Used:**

man man

man -k challenge

man wvbhehecte

/challenge/challenge  --wvbheh 252

**Output:**
Correct usage! Your flag: pwn.college{wvCIbh2ReX5hXecBt-eruOMgwsu.QX2EDO0wSO2QDM1EzW}

**Flag:**
 pwn.college{wvCIbh2ReX5hXecBt-eruOMgwsu.QX2EDO0wSO2QDM1EzW}

### Challenge: Helpful Programs

**Commands Used:**

/challenge/challenge --help

/challenge/challenge -p

/challenge/challenge -g 443

**Output:**
Correct usage! Your flag: pwn.college{A-4PDRFIkYDfswvaJ4saXCZVgbA.QX3IDO0wSO2QDM1EzW}

**Flag:**
 pwn.college{A-4PDRFIkYDfswvaJ4saXCZVgbA.QX3IDO0wSO2QDM1EzW}

### Challenge: Help for Builtins

**Commands Used:**

help challenge

challenge --secret M7VHZgbk

**Output:**
Correct! Here is your flag!
pwn.college{M7VHZgbkShuHCgHlKO8r6z2M-PO.QX0ETO0wSO2QDM1EzW}

**Flag:**
 pwn.college{M7VHZgbkShuHCgHlKO8r6z2M-PO.QX0ETO0wSO2QDM1EzW}






























































