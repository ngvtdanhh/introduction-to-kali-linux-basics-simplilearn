# 🌐 Demo – Nikto Web Scan

## 🎯 Objective
Identify vulnerabilities in a target web server.

## 🛠 Command
```bash
nikto -h http://192.168.1.20
```
## 📌 Explanation

-h → Target host

Nikto checks for outdated software, misconfigurations, and security issues.

## 📷 Expected Output

```pgsql
- Nikto v2.5.0
- Target IP: 192.168.1.20
- Target Hostname: web.local
+ Server: Apache/2.4.54
+ The X-Frame-Options header is not set.
+ The X-Content-Type-Options header is not set.
+ Allowed HTTP Methods: GET, HEAD, POST
```

Note: Requires legal permission for scanning.


