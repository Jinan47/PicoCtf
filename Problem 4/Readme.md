# Wave a flag


## Overview
Points: 10   
Catogory: General Skills

## Description
Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...

## Hints
1: Get the Flag accessible in your shell by entering the following command in the Termianl prompt: $ wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/flag.txt.en

2: Get the password using the txt uploaded in the same folder of this writeup

3: Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm

4: -h and --help are the most common arguments to give to programs to get more information from them!

5: Not every program implements help features like -h and --help.

## Aproach
1st, Download the program on the webshell using the 1st hint in the hints section

2nd, change the mod of the program using chmod +x warm

3rd, run the program using ./warm 

4th, ./warm -h to continue 

## Video Tutorial
Enter this [video]() to watch the tutorial on my channel

## Flag
picoCTF{b1scu1ts_4nd_gr4vy_755f3544}
