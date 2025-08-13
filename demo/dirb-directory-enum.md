# 📁 Demo – Dirb Directory Enumeration

## 🎯 Objective
Enumerate hidden directories on a web server.

## 🛠 Command
```bash
dirb http://192.168.1.30 /usr/share/wordlists/dirb/common.txt
```
## 📌 Explanation

URL: Target web server

Wordlist: Common directory/file names in Kali

## 📷 Expected Output

```cpp
---- Scanning URL: http://192.168.1.30/ ----
+ http://192.168.1.30/admin (CODE:200|SIZE:1024)
+ http://192.168.1.30/login (CODE:200|SIZE:768)
```

Note: Use responsibly on authorized systems.

