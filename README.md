# Super Kali Wordlist

Clear text passwords using Troy Hunt's Pwned Passwords V2 and using Mex666666 decrypted SHA1 hashes to actual passwords.



[Troy Hunt's Blog](https://www.troyhunt.com/ive-just-launched-pwned-passwords-version-2/)

[Mex666666 on hashkiller.co.uk](https://forum.hashkiller.co.uk/user-view.aspx?u=33407)



**IMPORTANT**
The wordlist file is almost 6GB so I split it up into smaller 100MB text files. You should clone the following repositories to get all the full password/word list file
*(Github limits repo size to 1GB and file size to 100MB)*,

- https://github.com/0xdec0de5/super_kali_wordlist

- https://github.com/0xdec0de5/super_kali_wordlist_02

- https://github.com/0xdec0de5/super_kali_wordlist_03

- https://github.com/0xdec0de5/super_kali_wordlist_04

- https://github.com/0xdec0de5/super_kali_wordlist_05

- https://github.com/0xdec0de5/super_kali_wordlist_06



## How to use it

For my purposes, I use this word/password list as a replacement for the much smaller password lists distributed with Kali Linux.


Once you clone this repo and the others *(02 - 06)*, you should merge all the text files into one large wordlist text file.



**Linux**

`cat password_list_part_01.txt password_list_part_02.txt > full_wordlist.txt`



**Windows**

`copy /b password_list_part_01.txt+password_list_part_02.txt full_wordlist.txt`