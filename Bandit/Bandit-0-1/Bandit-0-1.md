
Bandit Level 0 → Level 1
Level Goal

The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.
Commands you may need to solve this level

ls , cd , cat , file , du , find

TIP: Create a file for notes and passwords on your local machine!

Passwords for levels are not saved automatically. If you do not save them yourself, you will need to start over from bandit0.

Passwords also occasionally change. It is recommended to take notes on how to solve each challenge. As levels get more challenging, detailed notes are useful to return to where you left off, reference for later problems, or help others after you’ve completed the challenge.

############################################################################

While still logged into,

ssh -p 2220 bandit0@56.228.72.241

pw = bandit0

ls

cat readme

############################################################################

bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
