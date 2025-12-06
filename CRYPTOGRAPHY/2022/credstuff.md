# CHALLENGE: CREDSTUFF

**DIFFICULTY:** MEDIUM

**LINK:** [credstuff](https://play.picoctf.org/practice/challenge/261?category=2&originalEvent=70&page=1)

## DESCRIPTION
We found a leak of a blackmarket website's login credentials. Can you find the password of the user `cultiris` and successfully decrypt it?
Download the leak [here](https://artifacts.picoctf.net/c/151/leak.tar).
The first user in `usernames.txt` corresponds to the first password in `passwords.txt`. The second user corresponds to the second password, and so on.

## STEPS/SOLUTION

1. Before proceeding with the challenge, create a directory in the picoCTF webshell and navigate into the directory. 
2. Download the archive file by using **wget** command.
3. This is a tar archive file. So decompress the file by using the command, `tar -xvf leak.tar`. Here, x stands for execute; to execute the extraction operation, v stands for verbose; to print the information on the screen as the extraction happens and this includes what directories are created and where the files are located, f stands for file; remember, file name should only come after this f. 
4. Now if the ls command is executed, a directory called leak would have been created. Navigating into the directory, one would find the two files described in the description. 

