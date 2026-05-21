# Academy Machine – Ethical Hacking Project

## Description
This project demonstrates a complete ethical hacking workflow performed on the Academy vulnerable machine using Kali Linux.

## Features
- Reconnaissance and target identification
- Port scanning using Nmap
- FTP enumeration
- Web application testing
- File upload vulnerability exploitation
- Remote Code Execution (RCE)

## Tools & Technologies
- Kali Linux
- Nmap
- FTP
- PHP
- Linux Commands
- Web Exploitation

## Steps Performed

### 1. Reconnaissance
Identified the target IP address and verified connectivity between Kali Linux and the target machine.

### 2. Port Scanning and Enumeration
Used Nmap to identify open ports and running services.

Command:
nmap -sV 192.168.x.x

### 3. FTP Enumeration
Accessed FTP service and downloaded sensitive files from the server.

### 4. Web Application Login
Used discovered credentials to login into the Academy web application.

### 5. File Upload Vulnerability
Uploaded a PHP payload to test the file upload vulnerability.

### 6. Remote Code Execution (RCE)
Executed the uploaded PHP file from the upload directory.

## Result
Successfully demonstrated reconnaissance, enumeration, exploitation, and Remote Code Execution on the Academy machine.

## Conclusion
This project improved practical understanding of penetration testing and web application security vulnerabilities.
