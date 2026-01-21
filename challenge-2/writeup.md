It was given that i had to analyze the binary files in hexadecimal format so there were two ways to do it
1) Use an online hexeditor
after uploading the image to that, searched for flag using the shrotcut "ctrl + f" and found the answer.
2) Use command prompt
For that first I had to reach the image by opening the requird folders.
I used cd command for going inside each directory and finally got into challenge_2. 
Then I used the built in hex viewer, certutil -dump image.jpg and found the flag at the bottom. 


flag{jai_mahismathi}
