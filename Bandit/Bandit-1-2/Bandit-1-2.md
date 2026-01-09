Level Goal

The password for the next level is stored in a file called - located in the home directory
Commands you may need to solve this level

ls , cd , cat , file , du , find
Helpful Reading Material

    Google Search for “dashed filename”
    Advanced Bash-scripting Guide - Chapter 3 - Special Characters

###################################################################

From the last box bandit0, we got the PW for bandit1

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

We now need to ssh into bandit1

ssh -p 2220 bandit1@56.228.72.241

PW = ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

ls

we can see a file called -

To view the - file we need to use ./ as it allows you to read a file literally name - as in unix/linux you can name files -. Just using cat - and cat does not know what to do with it. I read you also can use cat -- - but that did not work for me. The -- tells a program/cmd that everything after it is a file name and not a flag.

cat ./-

The file list the PW: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

