# CHALLENGE: Corrupted File

**DIFFICULTY:** EASY

**LINK:** [Corrupted File](https://play.picoctf.org/practice/challenge/519?category=4&originalEvent=77&page=1)

## DESCRIPTION 
This file seems broken... or is it? Maybe a couple of bytes could make all the difference. Can you figure out how to bring it back to life?
Download the [file](https://challenge-files.picoctf.net/c_amiable_citadel/ee2ab6d61392fc085e2a8c2ae3a947597ffac5a9aac88f7b887813b0c2c010fb/file)

## STEPS/SOLUTION
The solution is discussed here after doing the challenge on picoCTF's brower webshell tool, as I'm a Windows user. Hence after changing the file format to JPEG (process will be told later in the solution/discussion), I've downloaded the file to my PC.

1. Opened the browser webshell and by using the wget `<link>` command, downloaded the file.
2. The filename will be **file**. Hence, to get the filetype of the downloaded file, we'll be using the command **file file**.
3. The command will return *data*. I didn't get much information from this, so proceeded to read the hint.
4. The hint asked me to check the file header. I learnt that the file header is actually the first few bytes that show up when you use a **hex dump utility** to display the raw binary data of a file.
5. I learnt that **xxd** is a good tool to view the file bytes of a file.
6. 
