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
