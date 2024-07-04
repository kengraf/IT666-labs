# IT666-labs

### TBDs
- ~~review the book by chapter to fill gaps~~
- ~~determine which 5 chapters get 2 lectures~~
- add 4-5 questions from book to lectures?
- ~~set lab order~~ and complete this page
- set lab tasks and outcomes
- set lab walkthrough for student presentators
- add pratice sites, chapter? or standalone filler? https://www.stationx.net/cyber-security-labs/
- set assignments in canvas reading, labs, final quiz, present lab,
- fix grading
- Parrot running on EC2
- AWS python sim of apigatewayv2 (chatgpt)
- HTB access to PAPER
- alientvault billiardyoda ken.graf@unh.edu strongpassword
- AWS EC2 ssh auth.log generation
- Do the RHINO hunt https://cfreds.nist.gov/all/NIST/RhinoHunt
  https://www.youtube.com/watch?v=gzWiWH4skRE
- add helpful links
  - https://explainshell.com/explain?cmd=ls+-ar#

### 1) [Parrot install](./parrot.md)
  - __Summary:__ For labs this semester we will use Parrot OS running in a virtual machine.  
  - __Tasks:__
    - Install VirtualBox and Parrot VM.
    - Demonstrate command line and browser connectivity to the Internet

### 2) [Pi exam](./pi.md)
  - __Summary:__ Attack a simple application [Pi Exam](https://pi.kengraf.com).  Modifying inputs to achieve different results.  
  - __Tools:__ Browser inspect.  
  - __Tasks:__ Inspect source, real answer, shortened answer, admin answer, cookie answer, injection answer.  

### 3) [OWASP Top 10 Web Attacks](./hacksplaining.md)
  - __Summary:__ [Hacksplaining](https://hacksplaining.com) is a free online site with live demos of the most common web attacks.  
  - __Tools:__ Browser.  
  - __Tasks:__ The class assignment is to complete the OWASP Top 10 scenarios.  Lead the class through 4-5 examples.  

### 4) [DNS Exfiltration](./dns_exfil.md)
  - __Summary:__ Demonstrate how to use valid DNS requests to communicate with an [attackers command and control](https://github.com/kengraf/DNSexfil/tree/main).  
  - __Tools:__ Parrot OS, python and nslookup.  
  - __Tasks:__ Execute a python program on local machine.  Send a base64 encoded message to local DNS server.  

### 5) [Phishing](./phishing.md)
  - __Summary:__ email (me)/KnowBe4/dkim/spf.  
  - __Tools:__ Parrot OS email.  
  - __Tasks:__ Configure email service on Parrot.  Send phishing email to selected target.  

### 6) [HTB: 2million](./htb_2million.md)
  - __Summary:__ To cellibrate 2 million users; Hack The Box (HTB) went retro. HTB use to require that "you are so high" to create an account on thier site.  This box is a simulation of HTB's previous login process.  Can you show that "you are so high"?.  
  - __Tools:__ Browser.  
  - __Tasks:__ Follow the code.  Alter the normal browser flow.  Get an access code to login.  

### 7) [HTB: Paper](./htb_paper.md)
  - __Summary:__ A step up in difficulty from 2million.  This box is a fun theme based on "The Office".  
  - __Tools:__ Browser.  
  - __Tasks:__ .  

### 8) [Reverse Engineering](./ghidra.md)
  - __Summary:__ GHIDRA.  
  - __Tools:__ Parrot, Ghidra.  
  - __Tasks:__ .  

### 9) [Blockchain](./blockchain.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 10) [Openssl](./openssl.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 11) [Authentication Events](./auth_log.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 12) [Openid/Oauth](./openid_oauth.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 13) [Tokens](./tokens.md)
  - __Summary:__ totp, google authenticator.  
  - __Tasks:__ .  

### 14) [Stride](./stride.md)
  - __Summary:__ stride TrackCovid/serverless.  
  - __Tasks:__ .  

### 15) [Docker](./docker.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 16) [Internet Scanning](./internet_scanning.md)
  - __Summary:__ BGP.HE against UNH.  
  - __Tasks:__ .  

### 17) [Gruyere](./gruyere.md)
  - __Summary:__ ZAP/Burp bug hunt.  
  - __Tasks:__ .  

### 18) [TOR](./tor.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 19) [Network Forensics](./network_forensics.md)
  - __Summary:__ Alice wireshark.  
  - __Tasks:__ .  

### 20) [Chromium SCAP/Ublock](./chromium.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 21) [Rhino Hunt](./rhino_hunt.md)
  - __Summary:__ 2.	NIST rhino hunt (SIFT?).  Computer Forensic Reference Data Sets (CFReDS) can be found at www.cfreds.nist.gov
  - __Tasks:__ .  

### 22) [Cloud OpSec](./cloud_opsec.md)
  - __Summary:__ .  
  - __Tasks:__ .  

### 23) [Metasploit](./metasploit.md)
  - __Summary:__ offsec: dc-1 (reverse shell).  
  - __Tasks:__ .  

### 24) [Password Audit Windows](./password_audit_windows.md)
  - __Summary:__ Perform a WIndows password audit on a simulated business environment.  
  - __Tools:__ Browser.  
  - __Tasks:__ locate, retrieve, and crack password hashes.  Force password reset for failed user passwords.  

### 25) [Password Audit Linux](./password_audit_linux.md)
  - __Summary:__ Perform a Linux application password audit on a simulated business environment.  
  - __Tools:__ Browser.  
  - __Tasks:__ locate, retrieve, and crack password hashes.  Force password reset for failed user passwords.  


