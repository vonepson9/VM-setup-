#  VM Security Tour with RDP Tutorial   
> Comprehensive walkthrough of securing a Windows VM environment  
> Includes setup of snapshots, encryption, firewall rules, and remote access  

##  Video Walkthroughs

- 🔹 [**Full VM Setup Tour (Google Drive)**](https://drive.google.com/file/d/1oyGOlBrOj8bHqkXd26WP9tcTmm1oQR6P/view?usp=sharing)  
- 🔹 [**RDP Setup Walkthrough (Loom)**](https://www.loom.com/share/9d31e7cdae36471aa1946e6f932a8d41?sid=51cf6ea6-a3eb-4dca-9608-811ae52b6798)

---

![OS](https://img.shields.io/badge/Windows_10_Pro-blue?logo=windows&logoColor=white)
![Tools](https://img.shields.io/badge/Snapshots-lightgrey?logo=virtualbox&logoColor=black)
![Tools](https://img.shields.io/badge/IP_Scanner-blue?logo=nmap&logoColor=white)
![Tools](https://img.shields.io/badge/Vulnerability_Scanner-red?logo=owasp&logoColor=white)
![Tools](https://img.shields.io/badge/Full_Disk_Encryption-black?logo=windows&logoColor=white)
![Tools](https://img.shields.io/badge/RBAC-purple?logo=microsoft&logoColor=white)
![Tools](https://img.shields.io/badge/File_Encryption-yellow?logo=windows&logoColor=black)
![Tools](https://img.shields.io/badge/Windows_Firewall-orange?logo=windowsdefender&logoColor=white)
![Tools](https://img.shields.io/badge/Web_Content_Filtering-green?logo=cloudflare&logoColor=white)
![Tools](https://img.shields.io/badge/IPS-teal?logo=snort&logoColor=white)
![Tools](https://img.shields.io/badge/Group_Policy-darkblue?logo=microsoft&logoColor=white)
![Tools](https://img.shields.io/badge/RDP-lightblue?logo=microsoft&logoColor=white)

---

##  Included Configurations

-  **Snapshots:** Efficiently manage VM states for quick recovery  
-  **IP Scanner:** Identify active hosts and potential vulnerabilities  
-  **Vulnerability Scanner:** Proactively detect security weaknesses  
-  **Full Disk Encryption (FDE):** Protect data at rest with encryption  
-  **Role-Based Access Control (RBAC):** Enforce least privilege access  
-  **File Encryption:** Secure sensitive files with encryption protocols  
-  **Windows Firewall:** Manage inbound/outbound traffic effectively  
-  **Web/Content Filtering:** Restrict access to unsafe web content  
-  **Intrusion Prevention System (IPS):** Detect and mitigate threats in real-time  
-  **Group Policy Management:** Apply consistent security policies across the VM environment  
-  **Remote Desktop Protocol (RDP):** Secure remote access configuration and management  

---

##  RDP Setup Guide

### Steps to Enable RDP on Windows VM:

1. **Enable Remote Desktop:**  
   - Navigate to **Settings** → **System** → **Remote Desktop**  
   - Toggle **Enable Remote Desktop** to ON  

2. **Configure Windows Firewall to Allow RDP:**  
   - Open **Start Menu**, search for `firewall`  
   - Select **Allow an app through Windows Firewall**  
   - Ensure **Remote Desktop** is enabled on appropriate network profiles (Private/Public)

3. **Optional: Assign Static IP Address:**  
   - Maintain a consistent IP for reliable remote connections  

4. **Verify RDP Access:**  
   - Use **Remote Desktop Connection** from the client machine  
   - Connect using `IP_ADDRESS:3389` and appropriate credentials  

---

##  Security Recommendations

- Use complex, unique passwords for all RDP-enabled accounts  
- Enable Network Level Authentication (NLA) for RDP sessions  
- Regularly create snapshots before applying major changes  
- Continuously monitor vulnerabilities and apply necessary patches  
- Encrypt all sensitive data to maintain confidentiality  

---

> _This documentation outlines essential configurations to establish a secure, manageable Windows VM environment suitable for professional IT operations._
