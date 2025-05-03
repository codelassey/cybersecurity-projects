<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=Beginner-Friendly+Guide+to+My+Penetration+Testing+Project!;Explained+in+simple+terms,+step+by+step.&font=Fira+Code&center=true&width=1200&height=80&color=00FF00&pause=1000">
</p>

# Beginner's Guide to My Cisco Ethical Hacker Capstone Project

This guide explains all the technical terms and steps I used in my capstone project in plain language—no prior hacking knowledge needed!

---

## What's This Project About?

This is a simulated hacking lab where I learned to test for security problems, just like ethical hackers do in real life. I completed **four mini-challenges**, each with a different security issue.

---

## Key Tools I Used (Explained Simply)

| Tool         | What It Does                                                             |
|--------------|--------------------------------------------------------------------------|
| **Kali Linux**   | A special version of Linux for ethical hacking tools.                    |
| **Firefox**      | Used to browse web pages in the lab.                                      |
| **DVWA**         | A purposely weak website I hacked to learn web attacks.                  |
| **Nmap**         | Like a radar that scans computers on a network.                         |
| **enum4linux**   | Helps gather information from Windows-like file sharing systems.         |
| **smbclient**    | Allows connecting to shared folders on other machines.                   |
| **dirb**         | Tries to guess hidden folders on websites.                              |
| **Wireshark**    | Lets you read and analyze network traffic like a detective.             |
| **CrackStation** | A website that helps guess weak passwords from their scrambled forms.   |
| **SSH**          | Securely connects you to other computers using the terminal.             |

---

## What I Did — Explained in Simple Language

### 1. **Challenge: Break into a Login System (SQL Injection)**

- I visited a vulnerable website.
- I typed a special command into a login box that tricked the site into showing hidden users.
- I found someone named **Bob Smith**, got his password, and used it to access a secret file.

**New Term**:  
**SQL Injection** – A trick where you write something in a website box that breaks the site's rules and gives you more access than you should have.

---

### 2. **Challenge: Find Hidden Web Folders (Directory Indexing)**

- I used a tool called `dirb` to guess secret folders on a website.
- Some folders let me see all their files, which shouldn't happen.
- One of them had a file with a secret code.

**New Term**:  
**Directory Indexing** – When a website shows a full list of files inside a folder—bad idea if private stuff is there!

---

### 3. **Challenge: Break into Shared Folders (SMB Enumeration)**

- I scanned a network to find computers sharing folders.
- I connected to one that didn't need a password.
- I found a secret text file with another code.

**New Term**:  
**SMB** – A way for computers to share files. If not secured, hackers can sneak in.

---

### 4. **Challenge: Analyze a Captured File (PCAP Analysis)**

- I opened a `.pcap` file—this records everything that happened on a network.
- Using a program called Wireshark, I found out where someone visited on the internet.
- I followed the same link and found the last hidden code.

**New Term**:  
**PCAP** – Like a video recording of internet activity that you can play back and study.

---

## What I Learned

- **Think like an attacker** to defend better.
- Simple mistakes (like bad passwords or open folders) can be dangerous.
- Tools like Nmap, Wireshark, and DVWA are powerful for learning.

---

## Want to Learn This Too?

If you're a beginner, start by:

- Installing **Kali Linux** in a virtual machine.
- Playing with **DVWA** for web hacking practice. (check pentesterlab on GitHub for vulnerable labs for your virtual machine.
- Exploring YouTube tutorials on **Wireshark**, **Nmap**, and **CrackStation**.

---

## Link to the Full Technical Report

For intermediate/advanced readers, check out the full detailed report here:  
**[Cisco Ethical Hacker Capstone Report](./README.md)**

---

Feel free to clone this repo and explore. Stay ethical and keep learning!