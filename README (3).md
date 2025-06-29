
# 🔥 Firewall Configuration Task (Linux - UFW)

## 🧠 Objective
Set up and test basic firewall rules on a Linux machine using UFW.

## 🛠 Tools Used
- **UFW** (Uncomplicated Firewall) on Ubuntu

## 📑 Files Included
- `ufw_rules.txt` — All UFW commands and output
- `screenshot_1.png` — Blocking rule added (port 23)
- `screenshot_2.png` — Telnet block test result
- `screenshot_3.png` — Final firewall rule list
- `README.md` — This documentation

## 📋 Commands Summary
```bash
sudo ufw enable
sudo ufw deny 23
sudo ufw allow 22
sudo ufw status numbered
sudo ufw delete deny 23
```

## 🔍 Firewall Summary
- UFW blocks all incoming traffic by default.
- Custom rules allow selective access or denial of services.
- Port 23 (Telnet) was blocked to prevent insecure access.
- SSH (Port 22) remained accessible to maintain remote control.

## 📁 Folder Structure
```
firewall-configuration-task/
├── ufw_rules.txt
├── screenshot_1.png
├── screenshot_2.png
├── screenshot_3.png
└── README.md
```
