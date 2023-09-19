Here i will do every lab from starting point (the key is a strong foundation)

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/799d0260-e2ad-43d9-84df-b78e21efe959)

First lab is a Meow

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/675ce43e-892d-48ed-bbcc-5d7f391ec3de)

1.What does the acronym VM stand for.
What i recomend in this lab is use mutch google, to search, the google let as know, for every question. 

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/4b480cb0-73c1-44c4-94ca-90fd6920701e)

2.What tool do we use to interact with the operating system in order to issue commands via the command line, such as the one to start our VPN connection? It's also known as a console or shell. 

We need think about, for example where you turn on ur openvpn to start this machine, on distrubion Linux, the answer is terminal.

3. What service do we use to form our VPN connection into HTB labs?
Witch out this u can't start your machine, this is a openvpn.

4. What tool do we use to test our connection to the target with an ICMP echo request? 
If you're not sure ur machine is working, how kind of tool you will use to test? the tool is ping.

5.What is the name of the most common tool for finding open ports on a target? 
I thing this is a most popular tool in CyberSec to scan ports, this is a nmap

6. What service do we identify on port 23/tcp during our scans? 
We need to turn on the nmap, and check what's running on this port, here is how to do it:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/13cd6f1b-0692-4788-ac75-dbcf976ff1ba)

For this test it will be enought, to check what we need in this example
The answer for the question is telnet 

7. What username is able to log into the target over telnet with a blank password? 
I test some users, this will be a root, if u don't know try by your self some users until you will figure out 

8. Submit root flag 
We need to know log in as root, and get your own, this machine is little bit laggi, after few secend you will get access to login into the telnet 

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/26b2ea8d-0c66-4ef2-8dea-a122252c82eb)

Let's go to the next lab Fawn

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/9b7ea116-2eb6-4c64-aca6-0b4b5b5470dc)

1. What does the 3-letter acronym FTP stand for? 
Let's go into the google and check what's that acronym mean

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/2a66d17b-c7c5-46ff-a09b-be6ef7881ae0)

We can find the answer for question in first link :P, this is a File Transfer Protocol

2. Which port does the FTP service listen on usually? 
We can check this use the nmap, we learn how to use nmap in the previouse task

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/06197c3c-6427-4fa5-acf6-744ebee26a1b)

here is the results nmap, the answer for this question is 21

3. What acronym is used for the secure version of FTP? 
We can also see the answer for this question in screan, in secend task, this is a sFTP

4.What is the command we can use to send an ICMP echo request to test our connection to the target? 

We also learn this in previouse lab, the answer is ping.

5. From your scans, what version is FTP running on the target? 
We can also know this from scan, i recomend use -sCV with this switch we will know what kind of version is running on the server, or --script=http-enum, this is my favorite switch to know what kind of software is running on the server. the answer is vsftpd 3.0.3

6. From your scans, what OS type is running on the target?
This is also in scan, the answer is Unix

7.What is the command we need to run in order to display the 'ftp' client help menu? 
ftp -h, this show use client help menu or if u you want more details use man ftp

8. What is username that is used over FTP when you want to log in without having an account?
This also we can know from scan.

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/185abd1e-8e51-419b-8557-dd67632fb9a6)

9. What is the response code we get for the FTP message 'Login successful'? 
First we need to log in into FTP as Anonymouse and there we can see response code.

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/a36b139c-598d-44fc-ae06-d2fb08304b54)

10. There are a couple of commands we can use to list the files and directories available on the FTP server. One is dir. What is the other that is a common way to list files on a Linux system. 
This work like on the linux, the command is ls

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/0e419a5f-eb4b-4eaa-aeaa-ead21f9aae13)

Or if you don't rember the command u can write in ftp help, this list all command on ftp.

11.What is the command used to download the file we found on the FTP server? 
If u can't figure out what command is this, google it, here is the answer

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/4ac7cc1c-4aab-44b6-afb8-5203f364d359)

12. Submit root flag
Here is step by step how i get the flag.txt

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/1ce6aeaf-5f1c-43cf-b770-99db12ae22ae)


No we will do Dancing, this a Windows machine

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/1b304331-8d2a-4272-bc1a-474176a1378a)

1. What does the 3-letter acronym SMB stand for? 
I don't rember this acronym, let google it, we got this:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/bcde07ab-c689-4c81-975f-97f3e1430331)

2. What port does SMB use to operate at? 
Let's turn on nmap and check on what port SMB running 
Here's the results of nmap, on this machine are many ports 

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/bf8ee7c7-ccdd-4f1f-949d-1ff958027c68)

But the answer for the question is 445

3. What is the service name for port 445 that came up in our Nmap scan? 
We can get the answer for this question from previouse scan.

4. What is the 'flag' or 'switch' that we can use with the smbclient utility to 'list' the available shares on Dancing? 
We can get this from smbclient --help, here is the answer:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/a1badedf-e6a3-47ed-b62b-285edb56250a)

5.How many shares are there on Dancing? 
Let's use what we learn, smbclient -L <IP>, and we got this.

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/f177e21a-967a-437b-b31d-16729e9e9e77)

6. What is the name of the share we are able to access in the end with a blank password? 
We can also know this from previouse screan, the answer is WorkShares

7.What is the command we can use within the SMB shell to download the files we find? 
The command is the same like on FTP, get

8. Submit root flag 
Here is step by step, how i get the flag.txt

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/e47d9cf7-dfc5-406b-b432-e295d4346b67)


No will do, Redeemer

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/054ced0a-ae4a-4f89-95ac-2f029363e6f6)

1. Which TCP port is open on the machine? 
That how you rember, let's turn on the nmap, witch out this u can't get the answer for this question :P But in this lab, the port very hight, we need to use -p- to scan all port. Rember we you using switch -p- this scan take somethimes a few minutes, because nmap must scan all ports areound 65000, but if you don't want wate to mutch time use nmap -p- --min-rate 5000 <IP>

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/2bc0a6c6-6783-45e7-b0a5-9f76c5eef646)

2.Which service is running on the port that is open on the machine? 
We can know this from previouse scan, the answer is redis

3.What type of database is Redis? Choose from the following options: (i) In-memory Database, (ii) Traditional Database.
Google it, we can here find the answer

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/cec7e946-b40c-44c6-923d-70a479bb40d3)

the answer is In-memory Database

4.Which command-line utility is used to interact with the Redis server? Enter the program name you would enter into the terminal without any arguments. 
We need go to into google and search something about it and i found on Redis CLI

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/8f5373e2-76f1-4e5f-abcc-cc26056dd23b)

5. Which flag is used with the Redis command-line utility to specify the hostname? 
We need to use redis-cli to find switch to specify the hostname

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/052d9a8f-0ccf-49be-8329-b89b1917a798)

6. Once connected to a Redis server, which command is used to obtain the information and statistics about the Redis server? 

I can't find anything but after log in into the redis i tryed info, and got a lot of information

7. What is the version of the Redis server being used on the target machine? 
We need to analyz a lot output information, but i found this 

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/6b308c6b-2914-4ce2-a5c9-13993b06715d)

8. Which command is used to select the desired database in Redis?
This work in mysql or other database, we can select by command SELECT :P

9. How many keys are present inside the database with index 0? 
We can take information from info, under KeySpace

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/7f0e4038-f36c-4e76-93a6-68b3492680d4)

10. Which command is used to obtain all the keys in a database?
We need to google it, here's the results:
The answer is KEYS *

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/c9d17fb1-3214-46fb-bd6d-f851fd915199)

11. Submit root flag 
We can get this flag by command GET flag

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/1266a074-00b8-4ff9-871a-e4917e147b58)


Now we will do lab:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/d2028226-dacc-44ac-96be-cb9ac8110128)

1. What does the 3-letter acronym RDP stand for? 
We need to ask google, what he thinking about it, let's do this.
I got the answer for the question, this is a Remote Desktop Protocol 

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/befc100e-8311-419d-8d6e-23bca4315150)

2. What is a 3-letter acronym that refers to interaction with the host through a command line interface? 
If u don't know the answer google it, but this is a CLI.
A command-line interface (CLI) is a text-based user interface (UI) used to run programs, manage computer files and interact with the computer. Command-line interfaces are also called command-line user interfaces, console user interfaces and character user interfaces.

3. What about graphical user interface interactions? 
A graphics-based operating system interface that uses icons, menus and a mouse (to click on the icon or pull down the menus) to manage interaction with the system.

4. What is the name of an old remote access tool that came without encryption by default and listens on TCP port 23? 
We can check this by turn on nmap, but i you maybe rember this is a telnet, always working on 23 port.
Here is the output from nmap, result, and that how i wrote on port 23 is telnet

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/9c5caf7f-52b3-43db-88b3-0a0a6f36d467)

5.What is the name of the service running on port 3389 TCP? 
We can take this from previouse scan, there we can see what's working on port 3389, this is a ms-wbt-server, is a RDP
here is the link, you can find there many ways to exploit RDP. https://book.hacktricks.xyz/network-services-pentesting/pentesting-rdp

6. What is the switch used to specify the target host's IP address when using xfreerdp? 
We can find this by command: help -h

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/e312c9c6-e761-4eac-a15f-e0fc507b32eb)

7. What username successfully returns a desktop projection to us with a blank password?
we can try this by trial and error method, after few secend i found this is Administrator, this user don't need any password to log in into RDP.

8. Submit root flag 
Here is the command how we can, log in into RDP
xfreerdp /f /u:Administrator /cert:ignore /v:10.129.1.13
And after when we connect to RDP, we can see on Desktop the flag

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/76915bb5-67cd-477d-ad8d-08a7b1923406)


The next machine is:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/04972dfa-83bf-4517-9dce-4d55b4d0a884)

1.Directory Brute-forcing is a technique used to check a lot of paths on a web server to find hidden pages. Which is another name for this? (i) Local File Inclusion, (ii) dir busting, (iii) hash cracking. 
This is so simply, the answer for this question is dir busting beacause: Directory bursting (also known as directory brute forcing) is a web application technology used to find and identify possible hidden directories in websites. This is done with the aim of finding forgotten or unsecured web directories to see if they are vulnerable to exploitation.

2.What switch do we use for nmap's scan to specify that we want to perform version detection 
We can check this by command nmap -h 

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/1947da03-5f9d-4f10-be4e-6795fb124612)

3. What does Nmap report is the service identified as running on port 80/tcp? 
We can check this by using nmap, here is the results:
And now we know on port 80 running http

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/c0cf3054-3072-4f9f-848e-5b3b138e0070)

4. What server name and version of service is running on port 80/tcp? 
From the previouse scan we know this is a nginx 1.14.2
Here is what is this nginx, from the website:NGINX is a well known open source project originally written by Igor Sysoev, a Russian engineer. Igor started the project in 2002 and made it public in 2004. Since that time NGINX has become a de‑facto standard for high‑performance, scalable websites. Tens of millions of active websites use NGINX, including 1 million busiest websites in the world. Companies like Airbnb, Box, Dropbox, Netflix, Tumblr, WordPress.com, and many others deploy NGINX for scalability and performance reasons.

5.What switch do we use to specify to Gobuster we want to perform dir busting specifically
This is a dir.

6.When using gobuster to dir bust, what switch do we add to make sure it finds PHP pages? 
gobuster -h, there we can find this: the answer is -x php

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/95260aa6-316a-4601-9416-8d4800000dda)

7. What page is found during our dir busting activities? 
We need to turn on gobuster and check this out, by this command:└─$ gobuster dir -w /usr/share/wordlists/dirb/common.txt -u http://10.129.196.196/ -x php
Here what i found, and also this is a answer for the question:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/1d3baad4-6c26-47eb-914d-9350fbb9794e)

8. What is the HTTP status code reported by Gobuster for the discovered page? 
The status code is 200, that how can see on previouse screan.
After check this page, i got the login panel.

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/5d837fbc-ce10-478e-91e1-3c86fc32a7a1)


9. Submit root flag 
We can do this by checking by typing random things until we log in into the web, or use hydra to bruteforce the login page, here how can do it.
hydra -l /usr/share/wordlists/rockyou.txt -p /usr/share/wordlists/rockyou.txt 10.129.196.196 http-post-form "/admin.php:username=^USER^&password=^PASS^:Wrong username or password."

You just need to analyze it and adjust it according to your needs

Here is the flag:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/326ec034-d259-4c7a-ad89-d7160813c94b)

Let's go another lab:

![obraz](https://github.com/Anogota/The-key-is-a-strong-foundation/assets/143951834/32c640c1-c2ca-4c09-990a-8ad0f0d26a6e)
