# CHALLENGE: HIDEME

**DIFFICULTY:** MEDIUM

**LINK:** [hideme](https://play.picoctf.org/practice/challenge/350?category=4&originalEvent=72&page=1)

## DESCRIPTION 
Every file gets a flag.
The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye [here](https://artifacts.picoctf.net/c/256/flag.png).

## STEPS/SOLUTION

1. Download the image file in the picoCTF webshell by using, `wget https://artifacts.picoctf.net/c/256/flag.png`, or directtly click the link to download the file into your own machine.
2. As the tag of this challenge in the picoCTF challenge platform is, **Steganography**, zsteg command was initially tried. This command is useful to check if any files are hidden in a given file. Command is, `zsteg flag.png`. or filename will change if any other files named, flag.png, was downloaded earlier.
3. This command would return hex data and this would reveal 
