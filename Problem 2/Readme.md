# Python Wrangling


## Overview
Points: 10   
Catogory: General Skills

## Description
Python scripts are invoked kind of like programs in the Terminal... Can you run [this Python script](https://github.com/Jinan47/PicoCTF/blob/main/Problem%203/ende.py) using [this password](https://github.com/Jinan47/PicoCTF/blob/main/Problem%203/password.txt) to get [the flag](https://github.com/Jinan47/PicoCTF/blob/main/Problem%203/flag.txt.en)?

## Hints
1: Get the Python script accessible in your shell by entering the following command in the Terminal prompt: $ wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py

2: $ man python

## Extra Hints
1: Get the Flag accessible in your shell by entering the following command in the Termianl prompt: $ wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/flag.txt.en

2: Get the password using the txt uploaded in the same folder of this writeup

## Aproach
1st, Download the python script using the 1st hint in the hints section.

2nd, Download the flag using the 1st hint in the extra hints section

3rd, Get the password from the password txt uploaded in the same folder of this writeup

4th, $ python3 ende.py

5th, $ python3 ende.py -d flag.txt.en

6th, Paste the password from the password txt

## Video Tutorial
Enter this [video](https://www.youtube.com/watch?v=WfO9vTn1BKo) to watch the tutorial on my channel

## Flag
picoCTF{4p0110_1n_7h3_h0us3_aa821c16}
