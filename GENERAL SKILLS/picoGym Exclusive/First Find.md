# CHALLENGE: FIRST FIND

**DIFFICULTY:** EASY

**LINK:** [FIRST FIND](https://play.picoctf.org/practice/challenge/320?category=5&difficulty=1&originalEvent=gym&page=1)

## DESCRIPTION
Unzip this [archive](https://artifacts.picoctf.net/c/500/files.zip) and find the file named 'uber-secret.txt'.

## STEPS/SOLUTION

1. First create a directory with the name of your wish by using the command, `mkdir <directory name>`. Then go into the created directory by using the command, `cd <directory name>`.
2. Then download the zip file by using the `wget https://artifacts.picoctf.net/c/500/files.zip` command.will 
3. The challenge has specifically asked me to find a file named, 'uber-secret.txt'.
4. You have to now know that a zip file might contain hidden files/directories. To list all the hidden files and directories, you need to use a specific command that will do this operation.
5. The one command that I know of that will do this operation without actually unzipping the zip file is, *unzip -la <file>*. This command will list all the files/directories in this zip file with all the nested directories listed.
6. Now unzip the zip file using the command, `unzip files.zip`. This will extract all the files of this zip file into a directory called files.
7. Search for the filename, 'uber-secret.txt', and you will find this file as the contents of a last expandable directory. Refer to [this image].
