# 🕵️‍♂️ Network Sniffer

![Python](https://img.shields.io/badge/Python-3.x-blue) ![License](https://img.shields.io/badge/License-MIT-green)

A **highly configurable**, Python-based network packet sniffer for Linux, capable of decoding Ethernet, IPv4, TCP/UDP/ICMP protocols, and displaying payload contents in human-readable form.

---

## 📋 Table of Contents

1. [Features]
2. [Prerequisites] 
3. [Installation]  
4. [Usage] 
5. [Configuration & Filters]
6. [Example Output]
7. [Extending & Contributing]  
8. [Security & Legal](
9. [License]  
10. [Author]  

---

## 🔥 Features

- **Layer-2 & Layer-3 parsing**: Ethernet (MAC), IPv4 headers  
- **Protocol decoding**: TCP, UDP, ICMP  
- **Hex/ASCII payload dump** with word-wrapping  
- **Command-line filters** (protocol, IP, port)  
- **Log to file** in JSON or text formats  
- **Colorized terminal output** (via `colorama`)  
- **Modular design**: Easy to add new protocol parsers  

---

## ⚙️ Prerequisites

- **OS**: Linux (supports raw sockets via `AF_PACKET`)  
- **Python**: 3.6+  
- **Permissions**: Must run as root for raw-socket access  

```bash
# Debian/Ubuntu
sudo apt update && sudo apt install python3 python3-pip

# Arch/BlackArch
sudo pacman -Syu python python-pip
