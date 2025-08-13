# 📚 Case Study – Applying Kali Linux in Lab

## 🎯 Scenario
A simulated company web server is hosted on `192.168.1.50`.  
Objective: Perform reconnaissance and identify potential weaknesses.

## 🛠 Steps Taken
1. **Reconnaissance**
   - `nmap -sV 192.168.1.50`
   - Found ports 22 (SSH), 80 (HTTP)

2. **Web Enumeration**
   - `nikto -h http://192.168.1.50`
   - Identified missing security headers

   - `dirb http://192.168.1.50`
   - Discovered `/admin` login panel

3. **Analysis**
   - Outdated Apache server version  
   - Admin panel exposed without MFA

## 📌 Lessons Learned
- Always patch web servers to latest version
- Restrict access to sensitive directories
- Enable security headers by default

---

⚠️ **Disclaimer**: This case study is for educational use only in a controlled lab.
