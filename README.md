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
---
---


   # 📱 Termux Tools

---

### 11. OpenSSH
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/OpenSSH_logo.svg" width="80"/>
</p>

```bash
pkg install openssh
ssh user@host
```

---

### 12. Htop
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Htop-logo.svg" width="80"/>
</p>

```bash
pkg install htop
htop
```

---

### 13. Tmux
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Tmux_logo.svg" width="80"/>
</p>

```bash
pkg install tmux
tmux
```

---

### 14. Clang
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/1/1a/LLVM_Logo.svg" width="80"/>
</p>

```bash
pkg install clang
clang --version
```

---

### 15. Make
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/GNU_Logo.svg" width="80"/>
</p>

```bash
pkg install make
make
```

---

### 16. CMake
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Cmake.svg" width="80"/>
</p>

```bash
pkg install cmake
cmake --version
```

---

### 17. Zip
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Zip_logo.svg" width="80"/>
</p>

```bash
pkg install zip
zip file.zip file.txt
```

---

### 18. Unzip
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Zip_logo.svg" width="80"/>
</p>

```bash
pkg install unzip
unzip file.zip
```

---

### 19. Tar
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/GNU_Logo.svg" width="80"/>
</p>

```bash
pkg install tar
tar -xvf file.tar
```

---

### 20. Netcat
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Netcat_logo.png" width="80"/>
</p>

```bash
pkg install netcat
nc -lvp 4444
```

---

### 21. Traceroute
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Internet-icon.svg" width="80"/>
</p>

```bash
pkg install traceroute
traceroute google.com
```

---

### 22. Whois
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Internet-icon.svg" width="80"/>
</p>

```bash
pkg install whois
whois example.com
```

---

### 23. DNSUtils
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Internet-icon.svg" width="80"/>
</p>

```bash
pkg install dnsutils
nslookup google.com
```

---

### 24. FFmpeg
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/FFmpeg_Logo.svg" width="80"/>
</p>

```bash
pkg install ffmpeg
ffmpeg -version
```

---

### 25. ImageMagick
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/90/ImageMagick_logo.svg" width="80"/>
</p>

```bash
pkg install imagemagick
convert image.png image.jpg
```

---

### 26. Neovim
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Neovim-mark.svg" width="80"/>
</p>

```bash
pkg install neovim
nvim
```

---

### 27. Ranger
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/GNU_Logo.svg" width="80"/>
</p>

```bash
pkg install ranger
ranger
```

---

### 28. Tree
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/GNU_Logo.svg" width="80"/>
</p>

```bash
pkg install tree
tree
```

---

### 29. Grep
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/GNU_Logo.svg" width="80"/>
</p>

```bash
pkg install grep
grep "text" file.txt
```

---

### 30. Sed
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/GNU_Logo.svg" width="80"/>
</p>

```bash
pkg install sed
sed 's/old/new/' file.txt
```

---

### 31. Awk
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/35/GNU_Logo.svg" width="80"/>
</p>

```bash
pkg install gawk
awk '{print $1}' file.txt
```

---

### 32. Nmap
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Nmap_logo.svg" width="80"/>
</p>

```bash
pkg install nmap
nmap target_ip
```

---

### 33. Tcpdump
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/d/db/Wireshark_Logo.svg" width="80"/>
</p>

```bash
pkg install tcpdump
tcpdump -i any
```

---

### 34. Python Pip
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="80"/>
</p>

```bash
pkg install python
pip install requests
```

---

### 35. Node Package Manager
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" width="80"/>
</p>

```bash
npm install express
```

---

### 36. Composer
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Composer_logo.svg" width="80"/>
</p>

```bash
pkg install composer
composer --version
```

---

### 37. Yarn
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/1/11/Yarn-logo-kitten.svg" width="80"/>
</p>

```bash
npm install -g yarn
yarn --version
```

---

### 38. SQLite
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/38/SQLite370.svg" width="80"/>
</p>

```bash
pkg install sqlite
sqlite3 database.db
```

---

### 39. MariaDB
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/68/Mariadb-seal-browntext.svg" width="80"/>
</p>

```bash
pkg install mariadb
mysql -u root
```

---

### 40. PostgreSQL
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg" width="80"/>
</p>

```bash
pkg install postgresql
psql
```

---

---

### 41. Docker CLI
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Docker_%28container_engine%29_logo.svg" width="80"/>
</p>

```bash
pkg install docker
docker --version
```

---

### 42. Rust
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Rust_programming_language_black_logo.svg" width="80"/>
</p>

```bash
pkg install rust
rustc --version
```

---

### 43. Java (OpenJDK)
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/en/3/30/Java_programming_language_logo.svg" width="80"/>
</p>

```bash
pkg install openjdk-17
java -version
```

---

### 44. Gradle
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/c/cb/Gradle_logo.svg" width="80"/>
</p>

```bash
pkg install gradle
gradle -v
```

---

### 45. Maven
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/5/52/Apache_Maven_logo.svg" width="80"/>
</p>

```bash
pkg install maven
mvn -v
```

---

### 46. Perl
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Perl_logo.svg" width="80"/>
</p>

```bash
pkg install perl
perl -v
```

---

### 47. Lua
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/Lua-Logo.svg" width="80"/>
</p>

```bash
pkg install lua
lua -v
```

---

### 48. Bash
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Gnu-bash-logo.svg" width="80"/>
</p>

```bash
pkg install bash
bash --version
```

---

### 49. Zsh
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Zsh_logo.svg" width="80"/>
</p>

```bash
pkg install zsh
zsh
```

---

### 50. Fish
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Fish_shell_logo.svg" width="80"/>
</p>

```bash
pkg install fish
fish
```

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


