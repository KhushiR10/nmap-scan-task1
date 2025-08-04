# nmap-scan-task1
Internship Task 1-Nmap scan
# Task 1 - Network Port Scanning with Nmap

## 🎯 Objective
To scan the local network using Nmap and identify live hosts and open ports to understand network exposure.

## 🛠 Tools Used
- Zenmap (GUI version of Nmap)
- Command Prompt

## 🔍 My Network Details
- IPv4 Address: 192.168.56.1
- Subnet Mask: 255.255.255.0 → CIDR: /24
- Scan Target: 192.168.56.0/24

## 🚀 Scan Process
1. Opened Zenmap
2. Target: 192.168.56.0/24
3. Profile: Intense Scan
4. After scan finished, copied the Nmap Output
5. Pasted into Notepad and saved as scan_results.txt

## 📋 Scan Results (Example)
| IP Address     | Open Ports        | Services               |
|----------------|------------------|------------------------|
| 192.168.56.1   | 135, 139, 445     | MSRPC, NetBIOS, SMB    |
| 192.168.56.100 | 22                | SSH                    |

## 🔐 Analysis
- Port 22 (SSH) should have strong passwords or key authentication
- Ports 139 and 445 (Windows file sharing) can be risky if not protected
- Devices should have firewalls enabled

## 📁 Files Included
- scan_results.txt: Output from the Nmap scan
- Screenshots (optional)

## ✅ Conclusion
This task helped me understand how to discover devices and open ports on a local network using Nmap, which is important for basic cybersecurity audits.
