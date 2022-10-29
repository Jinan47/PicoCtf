# Wave a flag


## Overview
Points: 10   
Catogory: General Skills

## Description
Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information...

## Hints
1: This program will only work in the webshell or another Linux computer.

2: To get the file accessible in your shell, enter the following in the Terminal prompt: 

`$ wget https://mercury.picoctf.net/static/a14be2648c73e3cda5fc8490a2f476af/warm`

3: Run this program by entering the following in the Terminal prompt: `$ ./warm`, but you'll first have to make it executable with `$ chmod +x warm`

4: -h and --help are the most common arguments to give to programs to get more information from them!

5: Not every program implements help features like -h and --help.

## Aproach
1: Download the program on the webshell using the 2nd hint in the hints section

2: Change the mod of the program using `$ chmod +x warm`

3: Run the program using `$ ./warm `

4: Pass a h using `$ ./warm -h` to continue 

## Video Tutorial
Enter this [video]() to watch the tutorial on my channel

## Flag
picoCTF{b1scu1ts_4nd_gr4vy_755f3544}
