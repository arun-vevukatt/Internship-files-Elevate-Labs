
# 🔍 Vulnerability Scan Summary

## 🛠 Tool Used
- Nessus Essentials (Free Version)

## 🎯 Scan Target
- Target: localhost (127.0.0.1)
- Scan Duration: ~45 minutes
- Scan Type: Full Vulnerability Scan

---

## 🚨 Key Vulnerabilities Found

| No. | Vulnerability                   | Severity | Description                                              | Suggested Fix                              |
|-----|----------------------------------|----------|----------------------------------------------------------|---------------------------------------------|
| 1   | SSL/TLS Version Detection       | Medium   | Weak SSL protocols (e.g., SSLv2/3) still enabled         | Disable SSLv2 and SSLv3 in service configs  |
| 2   | SMB Signing Not Required        | High     | Unsigned SMB sessions allowed                            | Enforce SMB signing in Group Policy         |
| 3   | Outdated Software Packages      | Medium   | Software packages are not updated                        | Regularly patch/update installed software   |
| 4   | Insecure Services Running       | High     | Exposed services could be abused remotely                | Disable or restrict access via firewall     |

---

## 🔧 Recommendations
- Run software updates regularly
- Disable insecure protocols
- Audit and restrict services using firewall or access control
