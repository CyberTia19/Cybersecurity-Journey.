Title: Fawn Walkthrough

Platform: HackTheBox

Difficulty: Easy

Date: July 26,2025

Status: Completed by watching a walkthrough video

🧰 Tools Used :
 nmap
 ftp

🪜 Step-by-Step Walkthrough :

1: Scan with nmap 

nmap -sV -sS -O -p21 ( target IP ) 

* Findings: 
port 21 (ftp) open 

2: Connecting to FTP ( anonymous login) 
ftp ( IP ) 

* Findings: 
was able to login as anonymous ,listed the files using ( ls ) , and found a file called (flag.txt) 

3: Downloading the flag 

get flag.txt

*Findings:

I downloaded the flag

4: Final output 

cat flag.txt

*Findings:
I got the flag ! 

💡 What I Learned
How to use ftp for anonymous login

How to explore and download files from an FTP server

The basics of enumeration with nmap

🧠 Note
I completed this box by following a walkthrough video.
I made sure to understand each step and took notes so I can try solving future boxes on my own.




