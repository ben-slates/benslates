<div align="center">

# ⚔️ benslates — Cyberdeck Portfolio OS

[![Live Website](https://img.shields.io/badge/Live%20Site-benslates.xyz-ff2a6d?style=for-the-badge&logo=google-chrome&logoColor=white)](https://benslates.xyz)
[![Offensive Security](https://img.shields.io/badge/Specialization-Red%20Teaming-9d4edd?style=for-the-badge&logo=kalilinux&logoColor=white)](https://benslates.xyz)
[![License: MIT](https://img.shields.io/badge/License-MIT-00f5a0?style=for-the-badge)](./LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-ben--slates-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ben-slates)

<p align="center">
  <b>A single-page cybersecurity portfolio featuring an interactive Kali Linux desktop simulation on desktop and an ultra-premium cyber-glassmorphic HUD interface on mobile.</b>
</p>

<p align="center">
  <a href="#-dual-experience-architecture">Architecture</a> •
  <a href="#-features">Features</a> •
  <a href="#-terminal-command-cheatsheet">Terminal Commands</a> •
  <a href="#-offensive-security-arsenal">Arsenal</a> •
  <a href="#-certifications--labs">Certifications</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-contact">Contact</a>
</p>

---

</div>

## 🌐 Live Website

Access the production deployment directly at:  
👉 **[https://benslates.xyz](https://benslates.xyz)**

---

## 🔮 Dual-Experience Architecture

This portfolio detects the client viewport and provides two specialized user experiences with zero external framework overhead:

### 🖥️ Desktop Mode (`> 768px`) — Kali Linux Desktop OS Simulation
- **Simulated Display Manager**: Kali-themed login prompt with terminal boot sequence.
- **XFCE-Inspired Window Manager**: Fully draggable, resizable, maximizable, and minimizable windows with active taskbar integration.
- **Interactive Terminal (`zsh` emulation)**: Full shell simulation supporting real commands, file operations, pipe-like execution, and easter eggs.
- **Simulated File System**: Custom virtual VFS supporting directories, file navigation, reading, and downloading assets (`resume.pdf`, certificates).
- **Integrated Apps**: Mousepad text viewer/editor, File Manager, Browser preview, and Live System Clock.

### 📱 Mobile Mode (`≤ 768px`) — Cyber-Glassmorphic HUD Interface
- **Telemetry System Tray**: Real-time HUD showing Kali distribution status, fluctuating CPU/RAM telemetry, and live green status beacon.
- **Bento Profile Card**: Profile photo (`me.jpg`) framed in dynamic multi-color neon aura rings, verified researcher badge, and academic credentials.
- **Horizontal Quick-Nav**: Instant 1-tap anchor navigation across sections (`About`, `Arsenal`, `Certs`, `Experience`, `Contact`).
- **Color-Coded Offensive Arsenal**: Categorized skill tags (Exploitation, Scripting, Network, Web Security).
- **Verified HTB Labs & Certs**: Direct PDF access for Hack The Box machine certificates and Cisco Networking Academy validations.
- **Signature Glassy Liquid Footer**: Frosted glass container with ambient liquid light orbs, security updates subscription form, and social channels.

---

## 💻 Terminal Command Cheatsheet

When accessing the terminal in Desktop Mode, the following commands are available:

| Command | Description |
| :--- | :--- |
| `help` | Lists all available terminal commands |
| `whoami` | Displays profile information and security background |
| `skills` / `tools` | Outputs offensive security toolkit and competencies |
| `certs` | Lists verified certifications and lab accomplishments |
| `cat <file>` | Reads the content of a file from the virtual file system |
| `ls [-la]` | Lists directories and files in current working path |
| `cd <path>` | Changes current directory in virtual file system |
| `clear` | Clears the terminal buffer |
| `matrix` | Toggles animated digital rain background |
| `neofetch` | Displays Kali Linux system specifications and ASCII art |
| `get resume.pdf`| Downloads official Curriculum Vitae (PDF) |
| `uname -a` | Prints Linux kernel release and system telemetry |

---

## 🛡️ Offensive Security Arsenal

<div align="center">

| Domain | Tools & Technologies |
| :--- | :--- |
| **Operating Systems** | Kali Linux, Parrot Security, Debian, Ubuntu Server, Windows Subsystem for Linux |
| **Exploitation & Red Teaming** | Burp Suite Pro, Metasploit Framework, Hashcat, John the Ripper, Hydra, SQLmap |
| **Network & Enumeration** | Nmap, Wireshark, Gobuster, Nikto, Netcat, TCPdump, Fierce, Ffuf |
| **Programming & Scripting** | Python 3, Bash / Shell Scripting, SQL, PowerShell, C/C++ |
| **Core Competencies** | Recon & OSINT, Web App Penetration Testing (OWASP Top 10), Privilege Escalation, Network Pivoting |

</div>

---

## 📜 Certifications & Verified Labs

- **Hack The Box** — *Mythical Machine* (`HTBCERT-3620BFA7E0`)
- **Hack The Box** — *Puppet Machine* (`HTBCERT-D149A5DFAD`)
- **Cisco Networking Academy** — *Getting Started with Cisco Packet Tracer*
- **Cisco Networking Academy** — *Introduction to Cybersecurity*

*(All PDF certificates are included in the repository under [`certs/`](./certs))*

---

## 📂 Project Structure

```bash
benslates/
├── index.html          # Core single-page application (Desktop OS + Mobile HUD)
├── me.jpg              # High-resolution profile avatar asset
├── mobile_bg.jpg       # Optimized wallpaper for mobile glass cards
├── wallpaper.png       # Desktop Kali Linux wallpaper
├── wallpaper1.png      # Alternate desktop background asset
├── favicon.svg         # SVG vector favicon
├── icon.png            # Apple touch & high-DPI icon
├── resume.pdf          # Official resume (PDF)
├── certs/              # Verified certification and lab credentials
│   ├── Mythical.pdf
│   ├── Puppet.pdf
│   ├── Getting_Started_with_Cisco_Packet_Tracer.pdf
│   └── Introduction_to_Cybersecurity.pdf
├── BRAND.md            # Brand usage and trademark attribution policy
├── README.md           # Project documentation and architectural overview
└── LICENSE             # MIT License
```

---

## 🚀 Quick Start (Local Setup)

Clone the repository and serve with any local HTTP server:

```bash
# Clone the repository
git clone https://github.com/ben-slates/benslates.git

# Navigate to project directory
cd benslates

# Launch local server using Python 3
python3 -m http.server 8080

# Or using Node.js npx
npx serve .
```

Open your browser and navigate to `http://localhost:8080`.

---

## 👨‍💻 Author

**Muhammad Umer Farooq** (*benslates*)  
*Cybersecurity Specialist & Offensive Red Teamer*  
Active at **Rynex Security**

- 🌐 Website: [benslates.xyz](https://benslates.xyz)
- 🐙 GitHub: [@ben-slates](https://github.com/ben-slates)
- ✉️ Email: [hello@benslates.xyz](mailto:hello@benslates.xyz) / [umerf2700@gmail.com](mailto:umerf2700@gmail.com)
- 📞 Direct: +92-321-9400902

---

## ⚖️ License & Brand Usage

- **Code & Assets**: Licensed under the [MIT License](./LICENSE).
- **Brand & Identity**: The name **benslates** and associated identity assets are protected under the [Brand Usage Policy](./BRAND.md).

<div align="center">
  <sub>the quieter you become, the more you are able to hear</sub>
</div>
