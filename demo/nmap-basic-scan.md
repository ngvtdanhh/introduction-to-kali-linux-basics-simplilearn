# 🖥 Demo – Nmap Basic Scan

## 🎯 Objective
Perform a basic network scan to identify live hosts and open ports.

## 🛠 Command
```bash
nmap -sV 192.168.1.0/24
```
## 📌 Explanation

-sV → Service/version detection

192.168.1.0/24 → Scan entire local subnet

## 📷 Expected Output

```kotlin
Starting Nmap 7.94 ( https://nmap.org ) at 2025-08-13
Nmap scan report for 192.168.1.10
Host is up (0.0020s latency).
PORT     STATE SERVICE VERSION
22/tcp   open  ssh     OpenSSH 8.9p1
80/tcp   open  http    Apache httpd 2.4.54
443/tcp  open  https   nginx 1.23
```

Note: Run only on authorized networks.
