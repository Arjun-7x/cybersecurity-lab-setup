# 🐦 Bonus: Parrot OS Installation Guide

If you made it this far… yeah, you’re not just curious anymore — you’re serious.

So as a bonus, let’s set up another powerful machine in your lab: **Parrot OS**.

Think of it as another hunter… silent, lightweight, and deadly in its own way.

And don’t worry — we’re using the same setup and requirements as before. Nothing new, just one more weapon in your arsenal.

---

## Step 1: Download Parrot OS (Virtual Machine)

- Go to the official Parrot OS website  
- Navigate to **Download → Virtual Machines**  
- Choose:
  - VirtualBox version **or**
  - VMware version  

> File size will be around 2–3GB. Let it download.

---

## Step 2: Extract the File

- Extract the downloaded `.zip` or `.7z` file  
- You’ll get a ready-to-use virtual machine file (`.ova`)

---

## Step 3: Import the Machine

### VMware:

- Open VMware Workstation Player  
- Click **Open a Virtual Machine**  
- Select the extracted file  
- Click **Import** and start it  

---

### VirtualBox:

- Open VirtualBox  
- Click **File → Import Appliance**  
- Select the `.ova` file  
- Click **Next → Finish**  

---

## Step 4: Boot and Login

Start the virtual machine.

Default credentials:
- Username: user
- Password: toor

---

## Step 5: Update the System

Open terminal and run:
sudo apt update && sudo apt upgrade -y

---

## Step 6: Adjust Settings (Optional but Recommended)

- Increase RAM to at least 4GB  
- Assign 2 CPU cores  
- Enable 3D acceleration if available  

> Smooth system = smoother workflow.

---

## 💀 Bonus Complete

Now your lab has:

- Kali Linux (main attacker)  
- Metasploitable 2 (target)  
- Parrot OS (secondary attacker / alternative toolkit)  

You’re no longer just setting up…  
You’re building an ecosystem.

Use it well.
