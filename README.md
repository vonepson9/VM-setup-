# 🖥️ VM Security Tour with RDP Tutorial 🔐  
> Deep dive into securing your Windows VM with all the pro moves  
> 🔥 Snapshots, scanners, encryption, firewalls & policies, oh my!

## 🎥 Video Walkthroughs

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

## 🔧 What’s Included

- 📸 **Snapshots** — Capture VM states, roll back like a boss  
- 🌐 **IP Scanner** — Find open ports and lurking threats  
- 🕵️ **Vulnerability Scanner** — Hunt down weaknesses before the bad guys do  
- 🔒 **Full Disk Encryption (FDE)** — Lock your drive down tight, no snooping  
- 🧑‍💼 **RBAC (Role-Based Access Control)** — Fine-tune who can do what, no admin overload  
- 🗂️ **File Encryption** — Encrypt files individually, next-level privacy  
- 🔥 **Windows Firewall** — Control inbound/outbound traffic like a pro  
- 🌐 **Web/Content Filtering** — Block sketchy websites before they even load  
- 🛡️ **Intrusion Prevention System (IPS)** — Detect & stop attacks in real-time  
- 🛠️ **Group Policy Tweaks** — Enforce security settings network-wide  
- 📡 **Remote Desktop Protocol (RDP)** — Secure remote access setup and management  

---

## 📚 Why This Matters

Cybersecurity ain’t a joke, it’s survival.  
This VM setup isn’t just theory — I’ve learned by breaking and fixing.  
Now you get the blueprint to level up your own game.

---

## 📝 RDP Setup Guide

Remote Desktop Protocol (RDP) steps  

### ✅ Steps to Enable RDP on Windows VM:

1. **Enable Remote Desktop:**  
   - Open **Settings** → **System** → **Remote Desktop**  
   - Toggle ON **Enable Remote Desktop**

2. **Allow RDP in Windows Firewall:**  
   - Open **Start Menu**, type `firewall`  
   - Click **Allow an app through Windows Firewall**  
   - Confirm **Remote Desktop** is allowed on **Private** and/or **Public** networks

3. **Optional: Set a Static IP Address**  
   - Keeps your VM’s IP consistent for easier access

4. **Test Your RDP Connection:**  
   - Use **Remote Desktop Connection** from your host machine  
   - Enter: `IP_ADDRESS:3389`  
   - Login with your VM credentials

---

## 🔐 Pro Tips to Lock It Down

- Use strong, unique passwords for RDP accounts  
- Enable Network Level Authentication (NLA) on RDP  
- Regularly snapshot before major changes  
- Keep vulnerability scanners running for fresh finds  
- Always encrypt sensitive data, no exceptions

---

> 💡 _Make it secure. Make it yours. Lock it down like a fortress._  
