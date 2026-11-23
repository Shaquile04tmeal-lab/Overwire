# OverwTheWire
Documentation of my experience solving some over the wire puzzles

Day1 (This was being done on another machine running kali Linux)

I chose to start with Bandit (https://overthewire.org/wargames/bandit/bandit1.html)

Level0 a simple SSH using the command {sudo ssh -p 2220 bandit0@bandit.labs.overthewire.org} adding the fingerprint and using password bandit0 

Afterwards i had to find a password using the filename readme. using the find command i tried to find it however it wouldnt complete.

So i tried doing research and found here (https://manpages.ubuntu.com/manpages/noble/man1/find.1.html) that using a directory name after i could 

Set the find command to search form that point up the tree. so i used the command {find / -name readme} which produced a lot of results

one of which was a directory i wont name for the sake of the game and but i then found and documented the password for when i had to log in another day 

