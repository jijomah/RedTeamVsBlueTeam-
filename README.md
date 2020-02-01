# RedTeamVsBlueTeam-
Cybersecurity/Penetration Testing

Introduction

Red Team/Blue Team
    In this security oriented style of event the red team attempts to capture a flag while the blue team attempts to defend the flag from being captured.
    
Summary

  In this case I acted as both the Red team and the Blue team. The Red team is the attacker that hacks into a vulnerable web server through Kali machine. Hidden in the web server is a file called flag.txt which contains the name of flag. The attacker then uses a reverse php to gain access to the web server to recover the flag.txt document. I accomplished this by identifying and exploiting vulnerabilties on a target machine with use of Kali tools such as Metasploit, Nmap, Hydra, and John The Ripper.       
  The Blue team is the defender that performs Wireshark analysis of information systems to make appropriate security countermeasures and I achieved this by creating a mitigation plan to prevent file injection and block brute forcing of passwords in order to secure the Web server after finding the attacker's IP address, the time of when and how long the attack happened, the vulnerability that was exploited to achieved the attack, the amount of Hydra method password cracking attempts that was used, the Wireshark packet where the attacker obtained the credentials, and identifying which malicious php file that attacker injected into the Webdav server.

Tasks Performed

Red Team Objectives:

•	Discover the lP address of the Linux server.

•	Locate the hidden directory on the server.

•	Brute force the password for the hidden directory.

•	Break the hash password with John the Ripper.

•	Connect to the server via Webdav.

•	Upload a reverse php connection payload.

•	Capture and show the flag to your instructor.

Blue Team Objectives:

Use Wireshark to open the Snort log on your Kali machine.
Look through the data and answer the following questions according to Wireshark:
•	How long did the attack last?

•	How many password attempts were made?

•	ln which packet was the correct password found?

•	In which packet was the shell placed onto the server?

•	In which packet was the shell activated?


Link to Presentation

https://drive.google.com/file/d/1egvShHRDCL_apz1AUuDPjkd3XmF9F92j/view?usp=sharing 

