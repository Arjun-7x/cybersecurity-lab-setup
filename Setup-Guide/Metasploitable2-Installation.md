
# Metasploitable 2 Installation Guide (The Victim Machine 💀)

After setting up our hunter — Kali Linux — it’s time to bring in the victim.

Metasploitable 2 is an intentionally vulnerable machine made for practice.  
We’re using the same setup and requirements as Kali, so let’s get straight into it.

---

## Step 1: Download Metasploitable 2

- Go to the official download page  
- Download the Metasploitable 2 `.zip` file (~250MB)

---

## Step 2: Extract the Files

- Extract the `.zip` using 7-Zip or WinRAR  
- You’ll get:
  - `.vmdk` (virtual disk file)  
  - `.vmx` (for VMware users)

---

## Step 3: Import the Machine

### VMware:

- Open VMware Workstation Player  
- Click **Open a Virtual Machine**  
- Select the `.vmx` file  
- Click **Play Virtual Machine**

---

### VirtualBox:

- Click **New**  
- Name: Metasploitable2  
- Type: Linux  
- Version: Ubuntu (32-bit)

- Assign RAM: 512MB minimum (1GB recommended)

- Select **Use an existing virtual hard disk file**  
- Choose the `.vmdk` file  

- Finish and start the VM

---

## Step 4: Boot and Login

Once started, login using:

- Username: msfadmin<br>
- Password: msfadmin

---

## Step 5: Find the IP Address

Inside Metasploitable, run:ifconfig
Look for:
inet 192.168.x.x

That is your target IP address.

---

## Step 6: Test Connection from Kali

Open Kali Linux and run:ping <Metasploitable-IP>

If you get replies, the connection is successful.

---

## Step 7: Safety Setup

- Use NAT or Host-Only network mode  
- Take a snapshot before testing exploits  
- Do not connect this VM to public networks  

---

## ✅ Lab Ready

Your Metasploitable 2 machine is now ready.  
You now have a complete lab with Kali Linux and a vulnerable target to practice on.
