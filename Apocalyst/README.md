Hack The Box Walkthrough - Apocalyst

Apocalyst - https://app.hackthebox.com/machines/57

Apocalyst is a standalone Linux box which requires careful enumeration and attention to details. 

Initial foothold can be obtained by creating a custom wordlist and downloading an "image.jpeg" file and extracting a password list. We can then use this password list to bruteforce web logon for a user.

Privilege Escalation is very easy and simple. We have "write" permissions to a very important system file.
