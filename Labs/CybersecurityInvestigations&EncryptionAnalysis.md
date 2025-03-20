# Cybersecurity Investigations Encryption Analysis

https://imgur.com/a/LYr29ph

<h2>Overview</h2>
In this lab, I played the role of a Security Analyst for the Hill Valley Police Department, investigating a series of cybercrimes committed by the Alphabet Bandit. The lab combined cryptography, digital forensics, and threat detection to uncover insider activity and secure sensitive police records.
Throughout the investigation, I applied both offensive and defensive cybersecurity techniques to identify vulnerabilities, decrypt hidden messages, and gather critical evidence.
</br>
</br>


<h2>Technical Skills</h2>
✅ OpenSSL & GPG Encryption/Decryption <br />
✅ Symmetric vs. Asymmetric Cryptography Analysis<br />
✅ Hashing & Integrity Verification (SHA, MD5)<br />
✅ File Integrity Auditing & Change Detection<br />
✅ Steganography Detection & Analysis<br />
✅ Digital Signature Verification<br />
✅ Network & System Monitoring<br />
✅ Password Cracking (Hashcat)<br />
✅ Forensic Investigation & Insider Threat Analysis<br />
✅ Linux Command-Line Security Tools<br />

<h2> Downloading Encrypted Message </h2>
I downloaded the encrypted message onto the virtual machine using the following wget command:
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/PGUlj4D.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/UWg95MG.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Secure Retrieval of Encryption Key and IV </h2>
To proceed with decrypting the previously downloaded encrypted message, I successfully retrieved the associated key and IV using wget. The command executed was:
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/lUZGAGQ.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/BB2ZceE.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Decrypting the Message Using OpenSSL</h2>
I used OpenSSL to decrypt the previously downloaded communication.txt.enc file using the key and IV provided. The decryption was performed with the following command, ensuring the use of the correct cryptographic parameters:
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/DVAoFz3.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Creating and Encrypting a Secure Message </h2>
I followed the steps to securely create, encrypt, and prepare the message for transmission. Below is the detailed process:
<br />
<br />

<b> 1. Writing the Message ("meetingplace.txt")  </b>
<br />
I created a message for my partner, letting them know about the secret meeting scheduled for tomorrow. The contents of the message did not include any real names and were written in a secure format.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/lKEU5NV.png" height="80%" width="90%" alt=""/>
<br />
<br />

<b> 2. Generating a New Key and IV with OpenSSL </b>
<br />
I created a new key and IV using OpenSSL for secure encryption. This is done with the following command:
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/fa2hDxV.png" height="80%" width="90%" alt=""/>
<br />
<br />

<b> 3. Encrypting the Message with OpenSSL </b>
<br />
I used the newly generated key and IV to encrypt the meetingplace.txt file with the following OpenSSL command:
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/Fhd5z2e.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Developing a Counter-Insider Strategy </h2>
I formulated a plan to identify and catch the insider and documented it in a securely created message file titled secret_idea.txt. The message was written using my code name to maintain anonymity.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/xmIOQWv.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Generating and Sharing an Encrypted Public Key </h2>
To establish a secure communication channel, I generated a key pair and exported my public key in an armored format to facilitate safe sharing with my partner. After key generation, I exported my public key in ASCII-armored format for easy sharing:
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/668H6im.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/wmVUaBK.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/a8t0Dpi.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Importing Partner’s Public Key for Secure Communication </h2>
To facilitate encrypted communication, I successfully imported my partner’s public key into my GPG keyring.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/6N4MVLo.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Encrypting the Secret Idea Message with Partner’s Public Key </h2>
To ensure the confidentiality of my secret idea, I encrypted the message using my partner's public GPG key and securely stored the encrypted file.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/644byhn.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Decrypting Partner’s Encrypted Message </h2>
After receiving my partner’s encrypted message, I successfully decrypted it using my private key to access the contents securely. Checked the contents of decrypted_secret_idea.txt to confirm the message was correctly decrypted and intact.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/ZnEGgfm.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/G0RJuqA.png" height="80%" width="90%" alt=""/>
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/TQxKqF1.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Extracting the Investigation Files </h2>
I successfully extracted the investigation files provided to me, ensuring all contents were properly retrieved and accessible for further analysis. 
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/hFuCvT9.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Generating MD5 Hashes for Investigation Files </h2>
To ensure file integrity and verification, I successfully generated MD5 hashes for all extracted investigation files and stored them in a single file named hashes.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/FRUaXin.png" height="80%" width="90%" alt=""/>
<br />
<br />
  
<h2> Verifying File Integrity with MD5 Hash Comparison </h2>
I performed an MD5 hash comparison to check for any changes in the extracted investigation files by comparing them with the original hash records.<br />
- Unchanged files: Displayed OK, meaning their integrity is intact.<br />
- Modified files: Displayed FAILED, indicating the contents were altered.<br />
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/hedy7El.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Identifying Modifications in Changed Files Using diff </h2>
After detecting file modifications through the MD5 hash comparison, I used the <b>diff</b> command to analyze what was changed in the modified files.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/oy3qctN.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Extracting Messages from Captain Strickland </h2>
I successfully located and extracted messages from Captain Strickland for further analysis.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/yF9PPZd.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2> Importing Public Key </h2>
I successfully imported Captain Strickland’s public key into my GPG keyring to enable secure communication and verification of signed messages.
<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />

<h2>  </h2>

<br />
<br />
<p align="center">
<img src="https://i.imgur.com/.png" height="80%" width="90%" alt=""/>
<br />
<br />
