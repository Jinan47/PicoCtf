# information


## Overview
Points: 10   
Catogory: Forensics

## Description
Files can always be changed in a secret way. Can you find the flag? [cat.jpg](https://github.com/Jinan47/PicoCTF/blob/main/Problem%205/cat.jpg)

## Hints
1: Look at the details of the file

2: Make sure to submit the flag as picoCTF{XXXXX}

## Extra Hints
1: exiftool is used to show the details of files in linux webshell

2: It's good to decode sometimes to get what you need

## Aproach
1: We shall look at the details of the jpg according to the 1st hint

2: Download the file on your webshell: 

`wget https://mercury.picoctf.net/static/b4d62f6e431dc8e563309ea8c33a06b3/cat.jpg`

3: Read the 1st hint then enter the following command: `exiftool cat.jpg`

4: Just look very well in the details

5: You will see that there is a [base64](https://en.wikipedia.org/wiki/Base64) text which is `cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9`

6: Decode it using [this website](https://www.base64decode.org)

## Video Tutorial
Enter this [video]() to watch the tutorial on my channel

## Flag
picoCTF{the_m3tadata_1s_modified}
