# 🧠 TryHackMe Writeups — sudo0xksh

Welcome to my **TryHackMe writeups repository**.  
This repo documents my journey through **Easy → Medium → Logic-heavy CTFs**, focusing on **methodology, enumeration, and real attacker thinking** — not blind tool spam.

No fake hype.  
No “just run metasploit”.  
Only **why something worked** and **how the chain was built**.

---

## 🗂️ Repository Structure

Each folder represents **one TryHackMe room**, containing a clean walkthrough/writeup explaining:
- Recon & enumeration
- Exploitation logic
- Privilege escalation
- Key learnings (the part most people skip)

---

## 🟢 Easy → Easy-Medium Writeups

These rooms build **strong fundamentals**.  
If your basics are weak, Medium will destroy you.

- 📁 **[Brute It](./Brute-it)** — brute force, SSH key abuse & sudo misconfig  
- 📁 **[Anonymous](./Anonymous)** — anonymous FTP → script abuse → SUID privesc  
- 📁 **[Source](./Source)** — Webmin RCE → instant root  
- 📁 **[Watcher](./Watcher)** — LFI chaining, FTP pivoting, backups → SSH key  
- 📁 **[Year Of The Rabbit](./Year%20Of%20The%20Rabbit)** — steg + brainfuck + sudo CVE  
- 📁 **[Smol](./Smol)** — WordPress plugin LFI → backdoored plugin → pivots  
- 📁 **[Wonderland](./Wonderland)** — import hijacking, PATH abuse, SUID GTFOBins  
- 📁 **[The Marketplace](./The%20Marketplace)** — logic flaws & enumeration-driven exploitation  

---

## 🟡 Medium Writeups (Real Thinking Starts Here)

These rooms require **chaining**, **logic**, and **patience**.  
Tools help, but thinking wins.

- 📁 **[0day](./0day)** — Shellshock → kernel privesc  
- 📁 **[Bookstore](./Bookstore)** — API abuse, LFI → debug console → SUID binary  
- 📁 **[Boiler](./Boiler)** — deep enumeration, Joomla abuse, SUID find  
- 📁 **[cmess](./cmess)** — subdomain discovery → CMS RCE → cron privesc  
- 📁 **[Pyrat](./Pyrat)** — Python code eval service → Git creds → root  
- 📁 **[UltraTech](./UltraTech)** — API command injection → Docker escape  
- 📁 **[HA:Joker](./HA:Joker)** — Joomla + backups → LXD container escape  
- 📁 **[Relevant](./Relevant)** — Windows SMB → web shell → token impersonation  
- 📁 **[Road](./Road)** — parameter tampering → file upload → LD_PRELOAD  
- 📁 **[NOX](./NOX)** — logic-based enumeration, Nagios abuse, Piet programming  

---

## 🔴 Logic / Brain-Melter Tier

These rooms don’t test tools — they test **mindset**.

- 📁 **[Looking Glass](./Looking%20Glass)** — cipher chains, port puzzles, lateral movement  
- 📁 **[Mr Robot](./Mr%20Robot)** — robots.txt supremacy, WordPress RCE, SUID nmap  
- 📁 **[SQHell](./SQHell)** — pure SQL Injection hell  
  - SQLi via forms  
  - SQLi via HTTP headers  
  - SQL Inception (nested queries)  
  - UNION not always your friend  

---

## 🧠 What This Repo Is About

- Enumeration > Exploits  
- Logic > Tools  
- Chaining > Single bugs  
- Real-world mindset > CTF speedrun mentality  

If you just want flags, this repo isn’t for you.  
If you want **to think like a security researcher**, welcome.

---

## 🚀 About Me

**Daksh Baweja**  
Security Researcher | CTF Player | Bug Bounty Learner  

- 📧 Email: dakshbaweja20@gmail.com  
- 🐙 GitHub: https://github.com/sudo0xksh  

---

## 🛡️ Deteroid

**Deteroid** is a community-driven platform for bug bounty hunters to:
- Share real program insights  
- Rate targets honestly  
- Collaborate without BS  

Built to help hackers **hunt smarter, not louder**.

📸 Instagram: https://www.instagram.com/deteroids/

---

## ☕ Final Note

CTFs are not about hacking machines.  
They’re about **hacking your own thinking**.

If this repo helped you even a little —  
mission accomplished. 😈🔥
