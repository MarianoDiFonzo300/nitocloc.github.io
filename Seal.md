MACHINE SEAL WALKTHROUGH

Enumeration:

Nmap scan:
![nmap_scan](img/nmap_scan)

Nmap scan shows there are 3 ports open. Lets go and browse the ip given to see what we can found:

![Seal webpage](img/webpage)

lets do a brute force attack with gobuster to see what we can find:

command: gobuster dir -u https://10.129.95.190 -w /usr/share/seclists/Discovery/Web-Content/common.txt

![gobuster](img/gobuster.png)
