# static-ifconfig

A simple command-line tool to manage **static IP addresses** on **Raspberry Pi** boards.  
Supports both modern **NetworkManager** (Bookworm and later) and legacy **dhcpcd** (Bullseye, Buster).

---

## 🚀 Features
- Set a static IP address for any interface (`eth0`, `wlan0`, etc.)
- Remove static IP (revert to DHCP)
- List current configurations
- Works automatically with **NetworkManager** (Bookworm+) or **dhcpcd** (older Raspberry Pi OS releases)
- Designed for **Raspberry Pi**, but can work on other Debian/Ubuntu systems

---

## 📦 Installation

Build and install the `.deb` package:
```bash
git clone https://github.com/<your-username>/static-ifconfig.git
cd static-ifconfig
dpkg -i build/static-ifconfig_0.1-1_all.deb
