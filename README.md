<h1>Password Strength Checker</h1>


<h2>Description</h2>
In this project, we will be building a Python script designed to assess the strength of passwords. The goal is to develop a tool that evaluates user passwords based on criteria such as length, the inclusion of uppercase and lowercase letters, numbers, special characters, and their commonality against a database of frequently used passwords. This exercise serves as a fundamental lesson in understanding the robustness of passwords and the importance of creating secure, hard-to-crack credentials. <br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Kali Linux</b> 

<h2>Takeaways</h2>

- <b>Python Script Development for MD5 Hash Cracking</b>: Successfully developed a Python script that deciphers MD5 hashes to reveal plain text passwords, emphasizing practical applications of cryptographic techniques. Demonstrated proficiency in utilizing Python's hashlib module, enhancing skills in creating security tools and understanding hash function vulnerabilities.

- <b>Testing and Verification of Script Functionality</b>: Acquired practical experience by rigorously testing the hash cracker against a custom password list, validating the script’s effectiveness in identifying the correct passwords. This process highlighted the importance of comprehensive testing in software development, ensuring the tool’s functionality and reliability in real-world scenarios.


<h2>Program walk-through:</h2>

<p align="center">
Python script code for MD5 hash cracker using nano text editor: <br/>
<img src="Python code.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />Created a .txt file containing list of possible passwords:  <br/>
<img src="list of passwords.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generated an MD5 hash tied to the password 'admin': <br/>
<img src="md5 hash example.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successful verification of code executing and identifying 'admin' as the password stored within the hash:  <br/>
<img src="verfication.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
