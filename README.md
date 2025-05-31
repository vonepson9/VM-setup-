# 🖥️ VM Security Tour 🔐

This VM tour covers everything I’ve set up from what I installed to how I did it. You’ll see tools and configs in action, including Snapshots, IP Scanners, Vulnerability Scanners, Full Disk Encryption (FDE), RBAC, File Encryption, Windows Firewall rules, IPS setup, Content/Web Filtering, and Group Policy tweaks.

---

## 🎥 Video Walkthrough

Watch the full configuration tour here:  
📹 [VM Setup Walkthrough](https://drive.google.com/file/d/1oyGOlBrOj8bHqkXd26WP9tcTmm1oQR6P/view?usp=sharing)

---

## 🔧 What’s Included

- 📸 **Snapshots**  
- 🌐 **IP Scanner**  
- 🕵️ **Vulnerability Scanner**  
- 🔒 **Full Disk Encryption (FDE)**  
- 🧑‍💼 **RBAC (Role-Based Access Control)**  
- 🗂️ **File Encryption**  
- 🔥 **Windows Firewall**  
- 🌐 **Web/Content Filtering**  
- 🛡️ **Intrusion Prevention System (IPS)**  
- 🛠️ **Group Policy**  

---

## 📚 Why This Matters

In the world of cybersecurity, hands-on skills are 🔑.  
This VM setup helped me learn, break, fix, and secure systems — and now I’m sharing it so you can do the same.

---

## 📝RDP Setup Guide

Remote Desktop Protocol (RDP) steps  
🎥 [Watch the RDP Setup Walkthrough](https://www.loom.com/share/9d31e7cdae36471aa1946e6f932a8d41?sid=51cf6ea6-a3eb-4dca-9608-811ae52b6798)  

### ✅ Steps to Enable RDP on Windows VM:

1. **Enable Remote Desktop:**
   - Open **Settings** → **System** → **Remote Desktop**
   - Toggle ON **Enable Remote Desktop**

2. **Make sure RDP is allowed on Windows Firewall:**
   - Open the **Start Menu**, type `firewall`
   - Click **Allow an app through Windows Firewall**
   - Make sure **Remote Desktop** is allowed on **Private** and or **Public** networks

3. **Optional: Set a Static IP Address**
   - Helps maintain a consistent IP for RDP access


4. **Test RDP Connection:**
   - Use **Remote Desktop Connection** on your host machine
   - Enter: `IP_ADDRESS:3389`
   - Login using the RDP credentials you created

---

Make it secure. Make it yours. 🛠️🔥  


