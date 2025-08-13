# ⚙️ Kali Linux Setup & Configuration

Kali Linux is a Debian-based distribution optimized for penetration testing and security research.

---

## 📌 1. Installation Options

- **Virtual Machine** – Install via VirtualBox or VMware (recommended for beginners).
- **Bare Metal** – Install directly on hardware for full performance.
- **Live Boot** – Run from USB without installing.

---

## 🔧 2. Post-Installation Steps

**Update System**
   ```bash
   sudo apt update && sudo apt upgrade -y
  ```

   ```bash
sudo adduser username
sudo usermod -aG sudo username
```
## Configure Network

Enable DHCP or set static IP

## Install Additional Tools

   ```bash
sudo apt install <tool-name>
```

