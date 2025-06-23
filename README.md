
#  Local Network Port Scan using Nmap

# Tools Used
- Nmap (installed from https://nmap.org/download.html)

# Scan Details
- Local IP range identified: 192.168.1.0/24
- Command used:
  bash
  nmap -sS 192.168.1.0/24 -oN scan_results.txt
 
- Type of scan: TCP SYN Scan (-sS)

# Findings
Example IPs and open ports:
- 192.168.1.1 → 80/tcp (HTTP), 443/tcp (HTTPS)
- 192.168.1.5 → 22/tcp (SSH), 445/tcp (SMB)

# Security Analysis
- Open port 22 (SSH): May allow brute-force login if not secured.
- Port 445 (Windows file sharing): Can be risky; disable if unused.

# Output
- Scan result saved in `scan_results.txt`
- Screenshots added for visual proof

##  Folder Structure

network-port-scan-task/
├── scan_results.txt
├── screenshot_1.png
├── screenshot_2.png
└── README.md

