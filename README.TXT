████████████████████████████████████████████████████████████████████████
█                                                                      █
█                  W E L C O M E   T O   Z O M B U N T U              █
█                                                                      █
████████████████████████████████████████████████████████████████████████
========================================================================
This project is a **fun and educational setup** of a deliberately 
vulnerable Ubuntu Server 18.04 virtual machine    
It is designed for practicing penetration testing, ethical hacking, and 
security hardening techniques in a controlled environment. I put this
together to help students get started testing security tools in an easy
manner without complexity. That said, it is a work in progress and is
distributed as is and for research purposes only.
!!!!!!!!!!!!!!!!!DISCLAIMER!!!!!!!!!!!!!!!!!!!!DISCLAIMER!!!!!!!!!!!!!!!
This VM is **intentionally vulnerable** and should **never** be exposed 
to the internet or in production. Use only in isolated environments.  
!!!!!!!!!!!!!!!!!DISCLAIMER!!!!!!!!!!!!!!!!!!!!DISCLAIMER!!!!!!!!!!!!!!!
========================================================================
## The machine includes the following vulnerable services and applications:  
- **DVWA (Damn Vulnerable Web App)** – Installed and configured
    - Browse to *http://localIPAddr/DVWA*
    - DVWA: https://github.com/digininja/DVWA
- **Mutillidae** – Installed and configured 
    - Browse to *http://localIPAddr/mutillidae/src*
    - Mutillidae: https://github.com/webpwnized/mutillidae
- **Vulnerable WordPress Site** – Installed, configured, no security
    - Browse to *http://localIPAddr/wordpress*
- **Weak FTP Server** – Allows anonymous logins   
- **Telnet Enabled** – Insecure remote access  
- **Firewall Disabled** – No network protection  
- **AppArmor Disabled** - No mandatory access control for applications
## SYSTEM
- Username: *admin01*
- Password: *password*
## MYSQL/MARIADB
- Username: *admin01*
- Password: *password*
## WORDPRESS DATABASE
- Database: *vulnwp*
- DB User: *wp_user*
- Password: *password*
- Password: password
