## ENPM634 - Penetration Testing

**Selected Homework Highlights**

### HW4: Operation Nightfall
Conducted a complete red-team penetration test across a multi-VM lab environment (Linux entry host → pivot host → Windows server). Achieved privilege escalation on the entry host using a SUID `find` binary, established persistence via a root cron job, performed lateral movement to the pivot host by extracting an SSH private key from a backup archive, and finally compromised the Windows server using discovered plaintext WinRM credentials with Evil-WinRM.  
**Tags:** `privesc`, `persistence`, `lateral-movement`, `suid`, `winrm`, `ssh-pivot`

### Midterm #2: Penetration Testing
Performed a comprehensive web application penetration test on the DevFlow platform. Successfully exploited SQL injection for authentication bypass, insecure file upload leading to server-side Python code execution (RCE), Insecure Direct Object Reference (IDOR) to access restricted private questions, and JWT token forgery to escalate to administrator privileges.  
**Tags:** `web-exploitation`, `sql-injection`, `file-upload-rce`, `idor`, `jwt-forgery`

### HW2: Active Reconnaissance Report
Executed thorough active reconnaissance on a target network using Nmap (full port scanning and service enumeration), Gobuster (web directory brute-forcing), custom NSE scripts for FTP anonymous login checking and SMTP user enumeration, plus in-depth analysis of HTTP headers, DNS records, and SSL certificates. Identified multiple flags through protocol-level intelligence gathering.  
**Tags:** `reconnaissance`, `enumeration`, `nmap`, `gobuster`, `custom-nse`

### OSINT Operation: The Paris Intercept
Solved a challenging open-source intelligence and geolocation task using a single nighttime street photograph from Paris. Identified the precise location (Maison Julien restaurant on Avenue Franklin D. Roosevelt) by cross-referencing visible signage, Parisian architecture, digital advertising displays, street elements, and trees with Google Maps and targeted searches.  
**Tags:** `osint`, `geolocation`, `image-analysis`, `visual-intelligence`
