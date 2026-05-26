## ENPM634 - Penetration Testing

**Full Red Team & Web Application Penetration Testing Coursework**  
University of Maryland, College Park

### HW4: Operation Nightfall
Executed a complete multi-stage red-team operation across three VMs (Linux entry → Linux pivot → Windows server).  
Achieved initial foothold via SSH, escalated to root using a SUID `find` binary, established persistence with a root cron job, performed lateral movement by extracting an SSH private key from a backup archive, and finally compromised the Windows server using discovered plaintext WinRM credentials via Evil-WinRM.  
**Tags:** `privesc`, `persistence`, `lateral-movement`, `suid`, `winrm`, `ssh-pivot`, `red-team`

### Midterm #2: Web Application Penetration Testing
Conducted an in-depth assessment of the DevFlow web application:  
- SQL injection for authentication bypass  
- Insecure file upload leading to server-side Python RCE  
- Insecure Direct Object Reference (IDOR) to access private admin notes  
- JWT token forgery to escalate to administrator privileges  
**Tags:** `web-exploitation`, `sql-injection`, `file-upload-rce`, `idor`, `jwt-forgery`, `broken-access-control`

### HW2: Active Reconnaissance Report
Performed comprehensive active reconnaissance on a target network: full port scanning with Nmap, web directory enumeration with Gobuster, HTTP header analysis, SMTP user enumeration, DNS record enumeration, SSL certificate inspection, and development of custom NSE scripts for FTP anonymous login checking and SMTP user enumeration.  
**Tags:** `reconnaissance`, `enumeration`, `nmap`, `gobuster`, `custom-nse`, `osint`

### HW3: Capture the Flag
Solved two CTF-style challenges:  
- Exploited an Insecure Direct Object Reference (IDOR) in a note-sharing app to access the admin’s secret note  
- Brute-forced a 4-digit PIN on a remote “Vault Lock” TCP service to retrieve the flag  
**Tags:** `ctf`, `idor`, `brute-force`, `binary-exploitation`

### King of the Hill Retrospective
Participated in a defensive “King of the Hill” exercise. Analyzed the opposing team’s persistence mechanisms (immutable files + cron-based token reclamation) and documented three successful attack vectors used (SSRF, IDOR, credential reuse) along with recommended security fixes.  
**Tags:** `defense`, `persistence`, `koth`, `post-exploitation`

### OSINT Operation: The Paris Intercept
Solved a pure open-source intelligence challenge using only a single nighttime street photograph from Paris. Identified the exact location (Maison Julien restaurant at 73 Avenue Franklin D. Roosevelt) by cross-referencing signage, architecture, digital advertising displays, and street elements with Google Maps and targeted searches.  
**Tags:** `osint`, `geolocation`, `image-analysis`, `visual-intelligence`

---

**Total Assignments:** 6 major reports covering active recon, web exploitation, red-teaming, OSINT, and defensive analysis.
