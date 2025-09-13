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

### 🔹 Download prebuilt `.deb`
You can download the package directly from GitHub Pages:

[➡️ Download static-ifconfig_0.1-1_all.deb](https://harshvijaykumarrawat.github.io/static-ifconfig/build/static-ifconfig_0.1-1_all.deb)

Then install it on your Pi:
```bash
wget https://harshvijaykumarrawat.github.io/static-ifconfig/build/static-ifconfig_0.1-1_all.deb
sudo dpkg -i static-ifconfig_0.1-1_all.deb
