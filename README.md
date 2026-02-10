---

## 🌐 Connect With Me

<p align="center">

<a href="https://www.instagram.com/cyber_x.n.7?igsh=NDg1cmM3YzRna3Rv" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

<a href="https://www.snapchat.com/add/munir0choudhary?share_id=06rXwOJAYdQ&locale=en-IN" target="_blank">
  <img src="https://img.shields.io/badge/Snapchat-FFFC00?style=for-the-badge&logo=snapchat&logoColor=black"/>
</a>

<a href="https://youtube.com/@different_life_77?si=vJ-UDpOMYXjg90rU" target="_blank">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
</a>

<a href="https://x.com/761751munir" target="_blank">
  <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=twitter&logoColor=white"/>
</a>

</p>

---




<h1 align="center">Munir Choudhary</h1>
<h3 align="center">Full Stack Developer • Backend Focused • MERN Stack</h3>

---

<p align="center">
Building secure, scalable and real-world web applications.
</p>

---

## 🧑‍💻 About Me

- 💻 I design and build backend systems  
- 🔐 Focused on authentication & secure APIs  
- 🚀 Learning advanced backend architecture  
- 🎯 Goal: Become a professional software engineer  

---

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nodejs,mongodb,js,html,css,tailwind,git,github,vscode" />
</p>

---

## 📊 GitHub Stats



<p align="center">
  <img src="https://www.kali.org/images/kali-dragon-icon.svg" width="200" />
</p>


---


---



---

---

## 🐉 Kali Linux Tools

---

### 🔍 NMAP – Advanced Scan
<p align="center">
<img src="https://www.kali.org/tools/nmap/images/nmap-logo.svg" width="100"/>
</p>

```bash
sudo apt update
sudo apt install nmap -y

# Service + Version detection
nmap -sS -sV -O -T4 target_ip

# Full port scan
nmap -p- target_ip
```

---

### 💣 Metasploit Framework
<p align="center">
<img src="https://www.kali.org/tools/metasploit-framework/images/metasploit-framework-logo.svg" width="100"/>
</p>

```bash
sudo apt install metasploit-framework -y
msfconsole

search vsftpd
use exploit/unix/ftp/vsftpd_234_backdoor
set RHOSTS target_ip
run
```

---

### 🕷 SQLMap
<p align="center">
<img src="https://www.kali.org/tools/sqlmap/images/sqlmap-logo.svg" width="100"/>
</p>

```bash
sudo apt install sqlmap -y
sqlmap -u "http://target.com/page.php?id=1" --dbs
```

---

### 🔐 Hydra
<p align="center">
<img src="https://www.kali.org/tools/hydra/images/hydra-logo.svg" width="100"/>
</p>

```bash
sudo apt install hydra -y
hydra -l admin -P passwords.txt ssh://target_ip -t 4
```

---

### 📡 Wireshark
<p align="center">
<img src="https://www.kali.org/tools/wireshark/images/wireshark-logo.svg" width="100"/>
</p>

```bash
sudo apt install wireshark -y
sudo wireshark
```

---

### 📶 Aircrack-ng
<p align="center">
<img src="https://www.kali.org/tools/aircrack-ng/images/aircrack-ng-logo.svg" width="100"/>
</p>

```bash
sudo apt install aircrack-ng -y
sudo airmon-ng start wlan0
```

---

### 🌐 Nikto
<p align="center">
<img src="https://www.kali.org/tools/nikto/images/nikto-logo.svg" width="100"/>
</p>

```bash
sudo apt install nikto -y
nikto -h http://target.com
```

---

### 📂 Gobuster
<p align="center">
<img src="https://www.kali.org/tools/gobuster/images/gobuster-logo.svg" width="100"/>
</p>

```bash
sudo apt install gobuster -y
gobuster dir -u http://target.com -w /usr/share/wordlists/dirb/common.txt
```

---

### 🔓 John The Ripper
<p align="center">
<img src="https://www.kali.org/tools/john/images/john-logo.svg" width="100"/>
</p>

```bash
sudo apt install john -y
john --wordlist=/usr/share/wordlists/rockyou.txt hash.txt
```

---


   # 📱 Termux Tools

---

## 1️⃣ Nmap
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Nmap_logo.svg" width="100"/>
</p>

```bash
pkg update
pkg install nmap
nmap -sV target_ip
```

---

## 2️⃣ Hydra
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5c/Hydra_logo.svg" width="100"/>
</p>

```bash
pkg install hydra
hydra -l user -P pass.txt ssh://target_ip
```

---

## 3️⃣ SQLMap
<p align="center">
<img src="https://sqlmap.org/images/sqlmap-logo.png" width="100"/>
</p>

```bash
pkg install python
pip install sqlmap
sqlmap -u "http://target.com?id=1" --dbs
```

---

## 4️⃣ Metasploit
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Metasploit_logo_and_wordmark.svg" width="100"/>
</p>

```bash
pkg install unstable-repo
pkg install metasploit
msfconsole
```

---

## 5️⃣ Wireshark (CLI alternative)
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/d/db/Wireshark_Logo.svg" width="100"/>
</p>

```bash
pkg install tcpdump
tcpdump -i any
```

---

## 6️⃣ Git
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Git-logo.svg" width="100"/>
</p>

```bash
pkg install git
git clone https://github.com/user/repo.git
```

---

## 7️⃣ Curl
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Curl_logo.svg" width="100"/>
</p>

```bash
pkg install curl
curl http://example.com
```

---

## 8️⃣ Wget
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/52/Wget_logo.svg" width="100"/>
</p>

```bash
pkg install wget
wget http://example.com/file.zip
```

---

## 9️⃣ Nano
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Nano_Logo.png" width="100"/>
</p>

```bash
pkg install nano
nano file.txt
```

---

## 🔟 Python
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="100"/>
</p>

```bash
pkg install python
python3
```

---

## 11️⃣ NodeJS
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" width="100"/>
</p>

```bash
pkg install nodejs
node -v
```

---

## 12️⃣ PHP
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg" width="100"/>
</p>

```bash
pkg install php
php -v
```

---

## 13️⃣ Netcat
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Netcat_logo.png" width="100"/>
</p>

```bash
pkg install netcat
nc -lvp 4444
```

---

## 14️⃣ WhoIs
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Internet-icon.svg" width="100"/>
</p>

```bash
pkg install whois
whois example.com
```

---

## 15️⃣ Traceroute
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Internet-icon.svg" width="100"/>
</p>

```bash
pkg install traceroute
traceroute google.com
```

---

## 16️⃣ HTTrack
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/7/77/HTTrack_logo.png" width="100"/>
</p>

```bash
pkg install httrack
httrack http://example.com
```

---

## 17️⃣ Aircrack-ng
<p align="center">
<img src="https://www.kali.org/tools/aircrack-ng/images/aircrack-ng-logo.svg" width="100"/>
</p>

```bash
pkg install aircrack-ng
aircrack-ng file.cap
```

---

## 18️⃣ John The Ripper
<p align="center">
<img src="https://www.kali.org/tools/john/images/john-logo.svg" width="100"/>
</p>

```bash
pkg install john
john hash.txt
```

---

## 19️⃣ Gobuster
<p align="center">
<img src="https://www.kali.org/tools/gobuster/images/gobuster-logo.svg" width="100"/>
</p>

```bash
pkg install gobuster
gobuster dir -u http://target.com -w wordlist.txt
```

---

## 20️⃣ Nikto
<p align="center">
<img src="https://www.kali.org/tools/nikto/images/nikto-logo.svg" width="100"/>
</p>

```bash
pkg install nikto
nikto -h http://target.com
```

---

  
## 📌 Current Focus

Building production-ready backend systems with clean architecture and security best practices.

---

<p align="center">
  ⭐ Thanks for visiting
</p>


