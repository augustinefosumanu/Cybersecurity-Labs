# Windows System Administration and Security Hardening - Good Corp, Inc.
(Ficticious Company)

<h1> Overview </h1>

This lab showcases key Windows administration and security tasks performed as a junior system administrator, ensuring compliance, security, and efficient system management. I Created users and groups, enforced password policies, and configured Active Directory. I also implemented GPOs, restricted unnecessary apps via PowerShell, and configured SIEM-compatible logging.</br>

<h2> Technical Skills </h2>

✅ User & Group Management </br>
✅ Access Control & Authentication </br>
✅ Group Policy Management (GPOs) </br>
✅ PowerShell Scripting </br>
✅ SIEM & Log Management </br>
✅ Windows Security Hardening </br>


<h2> Creating a Reports Folder on the Desktop </h2>
I executed the following command in the Windows Command Prompt to create a "reports" folder on the user's desktop
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/RRWZ9o2.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Creating a Text File </h2>
I executed the following command in the Windows Command Prompt to create a report.txt file with the title "Baselining Report" inside the reports folder
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/a6ZQHO2.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Appending Texts to a File </h2>
I executed the following command in the Windows Command Prompt to append a line "Created by [your name here]" to the report.txt file
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/TqoKtPd.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Using Environment Variables in the Command Line </h2>
To append the desired information (OS, date, and username) to the report.txt file using environment variables, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/5MJrAKL.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Enumerating Users </h2>
To enumerate all users on the system using the <b>net user</b> command, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/zn5f6rH.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Checking Password Status </h2>
To find the password status of the user Alex, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/4vjyCkk.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Enumerating Local Groups </h2>
To enumerate the local groups on the system using the <b>net localgroup</b> command, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/Ul5KOV8.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Retrieving Password Policy </h2>
To enumerate the current password policy using the <b>net accounts</b> command, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/1wTcey9.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Creating a Regular User </h2>
To create a regular user named <b>Anselm</b> with the password Ilovesales123! using the <b>net user</b> command in the Windows Command Prompt, I executed the following command
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/MqOzc5q.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Adding User to Administrators Group </h2>
To add user named <b>Anselm</b> to the Administrators group, I executed the following commands in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/xn4GYmD.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/8Kx2iq1.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/cO78xVP.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/lK6Uj2E.png" height="80%" width="90%" alt=""/>
<br />
<br />

  
<h2> Configuring Password Policies Using Group Policy Editor </h2>
I launch gpedit.msc (Group Policy Editor) and set password policies for the entire Windows machine
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/twgjtBV.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/6hHR51w.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/7vIIdRT.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Moving Files from User Directories to C:\ </h2>
To move the contracts folder from Alex's desktop to the C:\ drive, I executed the following command in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/pQf23Na.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/RXxqcAJ.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Creating Directories </h2>
To create the Backup, Script, and Log directories in the C:\ drive, I executed the following commands in the Windows Command Prompt
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/0riJBmr.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/1ezeqHJ.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Listing Available Event Logs </h2>
To retrieve the Security and Application logs using PowerShell and output the latest 100 events in JSON format to the C:\Log directory, I executed the following command and verified that all contents had been retrieved as specified
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/MhWCuLE.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/W2zFjYi.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/pS4C4wB.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Creating a PowerShell Script File </h2>
I created a PowerShell script called removepackages.ps1 to automate the uninstallation of packages listed in a CSV file named chocoactivity.csv. The script first imports the CSV using the Import-Csv cmdlet, and then loops through each package name using a foreach loop. For each package, the script runs the choco uninstall command with the -y parameter to automatically confirm the uninstallation. By executing this script, it initiates the uninstallation of the listed packages, streamlining the process of removing multiple packages efficiently.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/Gq0jEZz.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/tVkXIoS.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/44rnybi.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/8jxf8pI.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Setting Up Organizational Units in Active Directory </h2>
Using the Active Directory Users and Computers (ADUC) tool, I created a top-level GC Users organizational unit (OU) to manage department-specific user accounts. Within this OU, I established Finance sub-OU to organize users based on their respective departments.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/7cPlpdB.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/bzw1gzg.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/SJ78oNf.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/gKyMGED.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/Ja5Rzjz.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Creating a User Account for Bright in the Finance Organizational Unit</h2>
I created a new user account for Bright within the Finance Organizational Unit (OU) using Active Directory Users and Computers (ADUC). I set Bright's password to Ilovefinance!, ensuring it meets the necessary password policy requirements for the domain.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/WriG9RS.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/9ehQNeR.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/onioiIV.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/1AMpKNC.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Creating and Assigning Users to the Finance Group in Active Directory </h2>
In Active Directory Users and Computers (ADUC), I created a Finance group within the Finance organizational unit (OU). Then, I added the user Bright to the Finance group to ensure he has the appropriate access and permissions for the department.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/1fICxdX.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/mCD4YJG.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/IdALPbl.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/1E51V51.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/0x9Fic9.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/naVBb2Z.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/dRmbH7d.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Creating a Group Policy Object (GPO) Using Group Policy Management </h2>
I navigated to the Group Policy Management tool to create a Group Policy Object (GPO). The Group Policy Management tool, similar to the Active Directory Users and Computers tool, allowed me to configure and manage policies across the domain. This process ensures consistent settings and security measures for users and computers within the organization.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/DneoXwY.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Naming the GPO "Limit Settings </h2>
I created a Group Policy Object (GPO) and assign it the name Limit Settings. This GPO will be used to configure and manage specific policies within the Active Directory environment, allowing for streamlined management of settings and security configurations across designated users or computers
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/F9UCRHm.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/x9RNffP.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/RnalYrJ.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/kaxmS4h.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/SvKKRbO.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Linking a GPO to the Finance Organizational Unit </h2>
Once the Group Policy Object (GPO) had been enabled, I linked it to the Finance organizational unit (OU) to apply the policy settings specifically to users and computers within that department. This ensures that the designated configurations and restrictions are enforced for the Finance OU.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/Fxl9zI9.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/HNLF6PG.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/qf6C0PK.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Adding the Finance Group to the Remote Desktop Users Group </h2>
To grant remote desktop access to the Finance group, I used the Active Directory Users and Computers (ADUC) tool to add the Finance security group to the Remote Desktop Users group. This ensures that all members of the Finance group have the necessary permissions to access remote desktop sessions on the network.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/vh4kpqK.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/YXzd83D.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/8blvlgJ.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Refreshing Policy and Group Changes on a Windows 10 Machine </h2>
To ensure that the latest policy and group changes are applied, I refreshed the settings on the Windows 10 machine. This can be done by using tools like gpupdate to manually force a policy refresh, ensuring that any updates from Active Directory, group memberships, or security settings take effect immediately.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/Ars3waJ.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/ligIWr3.png" height="80%" width="90%" alt=""/>
<br />
<br />
<img src="https://i.imgur.com/9hmcfWY.png" height="80%" width="90%" alt=""/>
<br />
<br />
