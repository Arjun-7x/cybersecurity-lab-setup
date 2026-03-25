# Accessing DVWA on Metasploitable 2 ☠️

Alright, hacker… now things are about to get *spicy*.  
We’re stepping into our **hacker feast** — the DVWA is open, simmering with vulnerabilities, and just begging to be devoured 🍽️.  

If you’ve got Metasploitable 2 up and running, it’s time to meet **DVWA (Damn Vulnerable Web Application)** — your playground of controlled chaos.  

Prepare yourself… the feast is served.

---

## Step 1: Boot Metasploitable 2

Fire up your victim VM and log in:  
- Username: msfadmin
- Password: msfadmin
  
Think of it as waking your dinner… the target is alive and waiting.

---

## Step 2: Find the IP Address

Inside Metasploitable, run:ifconfig

Sniff out the `inet` address (e.g., `192.168.x.x`).  
This is the path to the feast — the address Kali will use to dig in.

---

## Step 3: Start the Web Server (if not running)

DVWA runs on Apache. Make sure the stove is hot:
sudo service apache2 status

If it’s off, light it up:
sudo service apache2 start

> DVWA won’t feed you if the kitchen is closed. Keep it running.

---

## Step 4: Access DVWA from Kali

1. Open a browser in Kali.  
2. Enter:http://<Metasploitable-IP>/dvwa

3. Feast your eyes on the login page.  

> The menu looks innocent, but everything here is tasty… and dangerous 😈

---

## Step 5: DVWA Default Credentials

Login like a sneaky diner:
- Username: admin
- Password: password

> Don’t worry — the chef expects you. These creds are intentionally weak.

---

## Step 6: Set the Security Level

Inside DVWA, pick your appetite:

- **Low** → appetizers (easy start)  
- **Medium** → main course (small challenges)  
- **High** → chef’s special (full spice, realistic attacks)  

> Start with the snacks, then graduate to the gourmet madness.

---

## ✅ DVWA Feast Ready

Your Kali machine is now the hungry diner, DVWA is the buffet, and the lab is your secret kitchen.  

Sink your teeth into SQLi, XSS, CSRF, and more — but remember:

- Only attack this VM  
- Never expose it to the internet  

The **DVWA is full**, the hacker feast awaits. Dig in and enjoy responsibly 😈.
