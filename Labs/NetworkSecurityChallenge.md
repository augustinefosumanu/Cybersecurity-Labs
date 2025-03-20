# Network Security Challenge: Investigating Anomalies at RockStar Corp

<h1> Overview </h1> 

In this lab, I conducted an in-depth investigation into unusual network behavior reported in RockStar Corp's Hollywood office. My analysis included identifying active network assets, performing vulnerability scans, executing penetration tests, and conducting forensic analysis. Through network reconnaissance, I discovered responsive IPs, analyzed open ports, and tested authentication mechanisms. Additionally, I examined DNS anomalies affecting access to rollingstone.com, analyzed packet captures for suspicious activity, and investigated unauthorized system modifications. </br>

<h2>Technical Skills:</h2>

✅ Network security (scanning, reconnaissance, and access control) </br>
✅ Ethical hacking & penetration testing (port scanning, authentication testing) </br>
✅ Digital forensics (packet analysis, intrusion detection) </br>
✅ Incident response (modification tracking, firewall investigation) </br>
✅ System administration & hardening (config file auditing, SSH security) </br>

<h2> Network Reconnaissance </h2> 
I used the <b>ping</b> command to check which IPs from the provided list were responsive.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/FbXY09R.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Identifying Open Ports </h2> 
I ran an Nmap SYN scan to find out the state of ports hosts within the Hollywood office’s responsive IP address.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/HTosbiF.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Gaining Access </h2> 
After discovering that port 22 was open, I accessed the server using SSH with the employee's username and password.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/BjuvyeD.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> DNS and Spoofing Investigation </h2> 
To determine why the company couldn't access rollingstone.com, I examined the hosts file to check for any tampering with a spoofed IP address.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/FPiNlmZ.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/fA2A7pW.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Analyzing Packet Captures </h2> 
In this step, I analyzed network traffic to detect suspicious activity that could indicate a security breach.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/lXBoa80.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/QC0jnXf.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/gyDwg9w.png" height="80%" width="90%" alt=""/>
<br />
<br />
