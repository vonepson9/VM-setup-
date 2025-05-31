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

> _"Security isn’t a product — it’s a mindset."_ 🧠

---

## 📝 README: RDP Setup Guide

Need Remote Desktop Protocol (RDP) access to your VM? Here’s how I set it up 💻⚡

### ✅ Steps to Enable RDP on Windows VM:

1. **Enable Remote Desktop:**
   - Open **Settings** → **System** → **Remote Desktop**
   - Toggle ON **Enable Remote Desktop**

2. **Allow RDP through Windows Firewall:**
   - Open the **Start Menu**, type `firewall`
   - Click **Allow an app through Windows Firewall**
   - Make sure **Remote Desktop** is allowed on **Private** and **Public** networks

3. **Optional: Set a Static IP Address**
   - Helps maintain a consistent IP for RDP access

4. **Set Up Port Forwarding (For NAT Network):**
   - Open your VM manager (e.g., VirtualBox/VMware)
   - Go to **Network settings** → **Port Forwarding**
   - Forward **Host Port 3389** to **Guest Port 3389**

5. **Create/Verify User Account for RDP:**
   - Ensure the account has a strong password
   - Preferably use an account with limited privileges

6. **Test RDP Connection:**
   - Use **Remote Desktop Connection** on your host machine
   - Enter: `IP_ADDRESS:3389`
   - Login using the RDP credentials you created

---

🎥 **Watch the RDP Setup Walkthrough (Loom Video):**  
[Click here to watch](https://www.loom.com/share/9d31e7cdae36471aa1946e6f932a8d41?sid=51cf6ea6-a3eb-4dca-9608-811ae52b6798)

---

Make it secure. Make it yours. 🛠️🔥  


