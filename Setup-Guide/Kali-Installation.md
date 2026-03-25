# Kali Linux Installation Guide (Virtual Machine - OVA Method)

Setting up Kali Linux inside a virtual machine is the safest and most efficient way to start your hacking lab. This guide walks you through installing Kali using a pre-built OVA file.

---

## Prerequisites

Before starting, make sure you have:

- Virtualization software:
  - VMware Workstation Player (free for personal use)  
  - OR Oracle VM VirtualBox (completely free)  
- At least 8GB RAM (16GB recommended)  
- 50GB+ free storage  
- Stable internet connection  

---

## Step 1: Download Kali Linux OVA File

1. Go to the official Kali Linux website.  
2. Navigate to **Downloads → Virtual Machines**  
3. Download the Kali Linux OVA file compatible with your virtualization software:  
   - VMware version  
   - VirtualBox version  

> The file size is large (~3–4GB). Be patient.

---

## Step 2: Extract the Downloaded File

- After downloading, extract the `.7z` or `.zip` file using 7-Zip or WinRAR  
- You’ll get a `.ova` file — this is your ready-to-use virtual machine  

---

## Step 3: Import Kali into Virtualization Software

### VMware:

1. Open VMware Workstation Player  
2. Click **“Open a Virtual Machine”**  
3. Select the `.ova` file  
4. Click **Import**

### VirtualBox:

1. Open VirtualBox  
2. Click **File → Import Appliance**  
3. Select the `.ova` file  
4. Click **Next → Finish**

---

## Step 4: Power On the Machine

- Start the virtual machine  
- Kali Linux will boot up automatically  

**Default Login Credentials:**

- Username: `kali`  
- Password: `kali`  

---

## Step 5: Initial Setup & Updates

Open terminal and run:

sudo apt update && sudo apt upgrade -y

## Step 6: Adjust VM Settings (Optional but Recommended)

For better performance:

- Increase RAM to 4GB–8GB  
- Assign 2+ CPU cores  
- Enable 3D Acceleration (if available)  

> Smooth performance = smoother hacking experience 😈

---

## Step 7: Verify Installation

Open terminal and test basic tools:

whoami
ifconfig
nmap --version

## Important Notes
Always use Kali inside a VM
Take snapshots before testing risky exploits
Keep your lab isolated from your main network when needed

💀 Your Kali VM is ready. Handle it responsibly.

