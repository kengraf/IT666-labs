# IT666-labs

### 1) Parrot install
  - __Summary:__ For labs this semester we will use Parrot OS running in a virtual machine.
  - __Tools:__ Virtual Box
  - __Tasks:__
    - Install VirtualBox and Parrot VM.
    - Demonstrate command line and browser connectivity to the Internet

### 2) Pi exam
  - __Summary:__ Attack a simple application.  Modifying inputs to achieve different results.  
  - __Tools:__ Browser inspect.
      Website: [Pi Exam](https://pi.kengraf.com)
  - __Tasks:__ Inspect source, real answer, shortened answer, admin answer, cookie answer, injection answer.  

### 3) OWASP Top 10 Web Attacks
  - __Summary:__ [Hacksplaining](https://hacksplaining.com) is a free online site with live demos of the most common web attacks.  
  - __Tools:__ Website.
            [Hacksplaining](https://hacksplaining.com)    
  - __Tasks:__ The class assignment is to complete the OWASP Top 10 scenarios.  Lead the class through 4-5 examples.  

### 4) DNS Exfiltration
  - __Summary:__ Demonstrate how to use valid DNS requests to communicate with an attackers command.
   - __Tools:__ Parrot OS, python and nslookup.  
  - __Tasks:__ Execute a python program on local machine.  Send base64 encoded messages to local DNS server.  

### 5) Phishing
  - __Summary:__ Experiment with email security standards.    
  - __Tools:__ Parrot OS email, dig, nslookup.  
  - __Tasks:__ Configure email service on Parrot.  Send phishing email to selected target.  

### 6) HTB: TwoMillion (foothold)
  - __Summary:__ To celebrate 2 million users; Hack The Box (HTB) went retro. In the past HTB required that "you are so high" to create an account on their site.  This box is a simulation of HTB's previous login process.  Can you show that you are tall enough to ride?   
  - __Tools:__ Browser.  
  - __Tasks:__ Follow the code.  Alter the normal browser flow.  Get an access code to login.  

### 7) HTB: TwoMillion (Ecalation)
  - __Summary:__ Continuation of previous lab   
  - __Tools:__ Browser 
  - __Tasks:__ Move laterally and escalate to root.  

### 8) Reverse Engineering
  - __Summary:__ Use NSA developed tool to decompile code.    
  - __Tools:__ Parrot, Ghidra.  
  - __Tasks:__ Compile sample C code, load executable in Ghidra, decompile and compare.  

### 9) Blockchain
  - __Summary:__ Use online demo to understand blockchain construction.      
  - __Tools:__ Website.
      [bitcoin demo](https://andersbrownworth.com/blockchain/distributed).
  - __Tasks:__ Alter transactions, track actions needed to bring the blocks back into agreement.  

### 10) Authentication SSH
  - __Summary:__ Create a cloud enabled server running SSH.
  - __Tools:__ AWS account, Parrot command shell.    
  - __Tasks:__ Create cloud machine, enable SSH, configure a specific user and keys.  

### 11) Authentication Events
  - __Summary:__ Analyze attacks against a public SSH server.  
  - __Tools:__ Parrot command line tools.
  - __Tasks:__ Retrieve auth log, analyze log for various attack behaviors.  

### 12) Authentication OAuth
  - __Summary:__ Understand single sign-on mechanisms for web sites.  
  - __Tools:__ Website.
      [kengraf-auth2](https://kengraf-auth2.web.app/github-popup.html)  
  - __Tasks:__  Social media login and analyze tokens.  

### 13) TOTP (Google Authenticator)
  - __Summary:__ Generate and analyze TOTP tokens used in apps like Google's Authenticator.
  - __Tools:__  Parrot, Python, Browser.    
  - __Tasks:__ Generate id, secret, and QR code.  

### 14) Docker
  - __Summary:__ Introduction to pulling and running an existing container.  
  - __Tools:__ Parrot command shell, Docker(podman), [DockerHub](dockerhub.com).  
  - __Tasks:__  Execute commands to pull, run, and manage containers.  

### 15) STRIDE
  - __Summary:__ Use Microsoft's STRIDE model and ThreatDragon to define threats for a basic web site.  
  - __Tools:__ Parrot, Docker(podman), [DockerHub](dockerhub.com).  
  - __Tasks:__ Add STRIDE threats to example ThreatDragon model.
        Submit screenshot.  

### 16) Internet Scanning
  - __Summary:__ Do reconnaissance against UNH using 3rd party Internet based tools.
  - __Tools:__  Websites
      [bgp.he.net](https://bgp.he.net/)  
      [shodan](https://www.shodan.io) 
  - __Tasks:__  Identify CIDR blocks, services, and websites.  

### 17) Gruyere
  - __Summary:__ A bug hunt against Google's Gruyere site
  - __Tools:__ Parrot, Burpsuite, and OWASP's ZAP.
        [Gruyere](http://google-gruyere.appspot.com/)  
  - __Tasks:__ Setup a proxy chain, evaluate site, test remediations.  

### 18) TOR
  - __Summary:__ Investigate how The Onion Router (TOR) works and navigation of the Dark Web.
  - __Tools:__  Parrot TOR browser
  - __Tasks:__ Analyze TOR circuits and visit a set of websites using TOR.    

### 19) Network Forensics
  - __Summary:__ Use Wireshark to analyze a packet capture.  
  - __Tools:__ Wireshark (preinstalled on Parrot)
  - __Tasks:__ By reading captured emails determine who Ann is meeting and where.  

### 20) Browser Policy
  - __Summary:__ Implement an enterprise security policy for Brave.  
  - __Tools:__  Brave install needed on Parrot
  - __Tasks:__ Chrome install, apply policy, make adjustments for unwanted behavior.
    - Disable sync, extensions, and password manager.
    - Force safe browsing
    - Enable "Dark Reader" extension    

### 21) Rhino Hunt
  - __Summary:__ 2.	A NIST sponsored forensic challenge called "Rhino Hunt".  Given a disk image and some network captures can you answer the questions and find the rhinos?
  - __Tools:__  Parrot: Wireshark and Foremost.  
  - __Tasks:__ Carve images and data from packet captures and a disk image.  

### 22) Cloud OpSec
  - __Summary:__ Investigate admin access (both by AWS and the customer) to and from a standard EC2 instance.  
  - __Tools:__ AWS cloud account, SSH.    
  - __Tasks:__ Create IAM roles and AWS EC2 instances.  Review SSH access. Review system manager access.    

### 23) KOTH Example
  - __Summary:__ A step up in difficulty from TwoMillion.  This box is a fun theme based on "The Office".  
  - __Tools:__ Parrot OS.  
  - __Tasks:__ Basic enumeration, searchsploit, LINPEAS.  

### 24) Password Audit
  - __Summary:__
    - Perform a Windows/Linux password audit on a simulated business environment.  
  - __Tools:__
    - [NICE portal](https://portal.nice-challenge.com/login) a registration link will be provided prior to class.  
    - Utilities needed are provided by a virtual Kali instance.  
  - __Tasks:__
    - Locate, retrieve, and crack password hashes.
    - Force password reset for only the users that failed the password audit.
