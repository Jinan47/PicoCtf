# Nice netcat


## Overview
Points: 15   
Catogory: General Skills

## Description
There is a nice program that you can talk to by using this command in a shell: `$ nc mercury.picoctf.net 43239`, but it doesn't speak English...

## Hints
1: You can practice using netcat with this picoGym problem: [what's a netcat?](https://play.picoctf.org/practice/challenge/34)

2: You can practice reading and writing ASCII with this picoGym problem: [Let's Warm Up](https://play.picoctf.org/practice/challenge/22)

## Extra Hints
1: **ASCII** is a text format

2: There is plenty of converters online

## Aproach
1: Enter the following command on your webshell: `$ nc mercury.picoctf.net 43239`

2: After reading the 2nd hint, we can conclude that the text we got after doing the 1st step is an **ASCII** text

3: We should convert it to an another text format, so enter [this link](https://www.dcode.fr/ascii-code), then just enter the  text

4: You'll have after hitting decode at the left the same text in different formats, the flag will appear clearly as the **dec** format

## Video Tutorial
Enter this [video]() to watch the tutorial on my channel

## Flag
picoCTF{g00d_k1tty!_n1c3_k1tty!_7c0821f5}
