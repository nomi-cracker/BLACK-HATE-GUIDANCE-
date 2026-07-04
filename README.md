
## all type of HACKING COURSE free & for educational purposes

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=FF0000&center=true&vCenter=true&width=700&lines=Android+Security+Research;Educational+Cybersecurity+Project;Built+by+NOMI+CYBER-X+TEAM" />

<br>

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Android%20%7C%20Windows-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-yellow?style=for-the-badge)

<br>

## 👥 NOMI CYBER-X TEAM

<a href="https://chat.whatsapp.com/Dv3fGKOzvuDI0hP4cqByEW?s=cl&p=a&mlu=3&amv=2">
<img src="https://img.shields.io/badge/WhatsApp-Join%20Community-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
</a>

<br><br>

**Building • Learning • Researching**

<br><br>
📋 TABLE OF CONTENTS
</dive>
╔══════════════════════════════════════════════════════════════════╗


║  1️⃣  TERMUX - COMPLETE SETUP & BASICS                          ║


║  2️⃣  KALI NETHUNTER - FULL INSTALLATION                        ║


║  3️⃣  KALI LINUX TOOLS (100+ TOOLS WITH USAGE)              ║


║  4️⃣  NETWORK HACKING TOOLS                                     ║


║  5️⃣  WEB HACKING TOOLS                                         ║


║  6️⃣  PHISHING TOOLS                                            ║


║  7️⃣  OSINT TOOLS                                               ║


║  8️⃣  ANDROID HACKING TOOLS                                     ║

║  9️⃣  WIFI HACKING TOOLS                                        ║


║ 10️⃣  ENCRYPTION & ANONYMITY TOOLS                              ║


║ 11️⃣  EXTRA ADVANCED TOOLS                                      ║


║ 12️⃣  TROUBLESHOOTING & TIPS                                    ║


║ 13️⃣  BUG BOUNTY & REAL-WORLD USAGE                             ║
╚══════════════════════════════════════════════════════════════════╝


1️⃣ TERMUX - COMPLETE SETUP

╔══════════════════════════════════════════════════════════════════╗


║             


📱 TERMUX BASICS & INSTALLATION                   

║


╚══════════════════════════════════════════════════════════════════╝

🔹 TERMUX KYA HAI?
Termux ek Android terminal emulator hai jo Linux environment provide karta hai. Iske through aap apne mobile ko hacking machine bana sakte ho.



🔹 TERMUX INSTALL KAREN



STEP 1: 

F-Droid se Termux install karo
      
❌ Google Play Store ka Termux outdated hai
       
✅ F-Droid (https://f-droid.org) se install karo
        

STEP 2: Storage permission do
        termux-setup-storage
        


STEP 3: Update & Upgrade
        pkg update && pkg upgrade -y
        

STEP 4: Basic packages install karo
        pkg install -y git curl wget python 
        
        python2 python3
        pkg install -y openssh nmap zsh 
        
        neovim nano
        pkg install -y clang make cmake 
        
        build-essential
        pkg install -y nodejs golang ruby 
        
        perl php
        pkg install -y binutils coreutils 
        findutils


🔹 TERMUX EXTRA PACKAGES


# Graphics & Display
pkg install -y x11-repo tur-repo
pkg install -y tigervnc xfce4 firefox

# Development
pkg install -y openjdk-17 gradle maven
pkg install -y rust cargo

# Database
pkg install -y mariadb postgresql sqlite

# Networking
pkg install -y net-tools dnsutils traceroute
pkg install -y hydra john aircrack-ng

# Media
pkg install -y ffmpeg imagemagick

# Python Libraries
pip install requests beautifulsoup4 selenium
pip install scapy colorama termcolor
pip install paramiko pwntools cryptography
pip install flask django fastapi
pip install numpy pandas matplotlib




🔹 TERMUX CUSTOMIZATION


# Oh My Zsh install karo
pkg install -y zsh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Color scheme
git clone https://github.com/termux/termux-styling
cd termux-styling
bash install.sh

# Fonts
pkg install -y fontconfig
fc-cache -fv

# Plugins
git clone https://github.com/zsh-users/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting



2️⃣ KALI NETHUNTER - FULL INSTALLATION


╔══════════════════════════════════════════════════════════════════╗
║            



🐉 KALI NETHUNTER COMPLETE SETUP             


║
╚══════════════════════════════════════════════════════════════════╝



METHOD 1: NETHUNTER (KALI IN TERMUX)


# Step 1: Install Nethunter Repo
pkg install -y wget
wget -O install-nethunter-termux https://offs.ec/2MceZWr
chmod +x install-nethunter-termux
./install-nethunter-termux

# Step 2: Install Kali (Full)
nethunter

# Step 3: Update Kali
apt update && apt full-upgrade -y

# Step 4: Essential Tools
apt install -y kali-linux-default
# OR light version
apt install -y kali-linux-headless

# Step 5: GUI Mode (VNC)
nethunter kex skey
nethunter kex start




METHOD 2: NETHUNTER PROOT (LIGHTWEIGHT)


# Proot Distro Install
pkg install -y proot-distro
proot-distro install kali

# Login
proot-distro login kali

# Inside Kali
apt update && apt upgrade -y
apt install -y kali-linux-core


METHOD 3: NETHUNTER ROOT (ROOTED PHONES)

# Requirements: Rooted Android + Custom Kernel
# Step 1: Download Nethunter image from offsec.com
# Step 2: Flash via TWRP/OrangeFox recovery
# Step 3: Install Nethunter app
# Step 4: Full Kali with GUI and all tools


3️⃣ KALI LINUX TOOLS - MASTER LIST


╔══════════════════════════════════════════════════════════════════╗
║       



🔧 100+ TOOLS WITH COMMANDS & USAGE                   


║
╚══════════════════════════════════════════════════════════════════╝



🕵️ INFORMATION GATHERING (RECON)


╔══════════════════════════════════════════════════════════════════╗


║ TOOL          | COMMAND                          | USE          ║
╠══════════════════════════════════════════════════════════════════╣



║ NMAP          | nmap -sS -sV -A target.com      | Port Scan     ║


║ ZENMAP        | zenmap                          | GUI Nmap      ║


║ NETDISCOVER   | netdiscover -r 192.168.1.0/24   | Network Scan  ║


║ MASS CAN      | masscan 192.168.1.0/24 -p80     | Fast Scan     ║


║ RUST SCAN     | rustscan -a target.com          | Fast Port     ║


║ DNSENUM       | dnsenum target.com              | DNS Enum      ║


║ DNSTRACE      | dnstrace -d target.com          | DNS Tracing   ║


║ THE HARVESTER | theharvester -d target.com      | Email/Sub     ║


║ SUBLIST3R     | sublist3r -d target.com         | Subdomains    ║


║ AQUATONE      | aquatone-discover -d target.com | Subdomain     ║


║ RECON-NG      | recon-ng                        | Framework     ║


║ SPIDER FOOT   | spiderfoot -s target.com        | OSINT         ║


║ AMASS         | amass enum -d target.com        | Subdomain     ║


║ SHODAN        | shodan search target.com        | IoT Search    ║


║ CENSYS        | censys search target.com  
| Asset Search  ║



╚══════════════════════════════════════════════════════════════════╝



🔐 VULNERABILITY ANALYSIS


╔══════════════════════════════════════════════════════════════════╗
║ TOOL            | COMMAND                      | USE            ║
╠══════════════════════════════════════════════════════════════════╣
║ OPENVAS        | openvas-start                 | Vuln Scanner   ║
║ NESSUS         | nessus -i                     | Vuln Scanner   ║
║ NIKTO          | nikto -h target.com           | Web Vuln       ║
║ WPS CAN        | wpscan --url target.com       | WordPress      ║
║ JOOMSCAN       | joomscan -u target.com        | Joomla         ║
║ DRUPAL SCAN    | droopescan scan drupal -u URL | Drupal         ║
║ CMSMAP         | cmsmap -u target.com          | CMS Scan       ║
║ WHATWEB        | whatweb -v target.com         | CMS Detect     ║
║ WAPITI         | wapiti -u target.com          | Web Vuln       ║
║ VULNERS        | vulners -s target.com         | CVE Check      ║
╚══════════════════════════════════════════════════════════════════╝
