# Suspicious Browser Extensions Audit Report

## Objective
To identify and remove potentially harmful or unnecessary browser extensions and understand the risks associated with malicious extensions.

## Tools Used
- Google Chrome (Extensions Manager: `chrome://extensions/`)
- Mozilla Firefox (Add-ons Manager: `about:addons`)

---

## Steps Performed

1. Opened browser's extension manager.
2. Reviewed installed extensions.
3. Checked permissions and reviews of each extension.
4. Identified unused or suspicious extensions.
5. Removed those that were not necessary or potentially harmful.
6. Restarted the browser to observe performance changes.
7. Researched threats from malicious browser extensions.

---

## Extensions Reviewed

| Extension Name | Purpose | Permissions | Status | Notes |
|----------------|---------|-------------|--------|-------|
| AdBlock | Blocks ads | Access to all websites | Kept | Trusted and useful |
| PDF Converter Free | Converts files | Access to file URLs | **Removed** | Suspicious origin, no reviews |
| Weather Tab | Displays weather info | Reads browsing history | **Removed** | Unnecessary and intrusive |
| Grammarly | Grammar assistance | Access to typed text | Kept | Reviewed and safe |
| Dark Reader | Dark mode for websites | Minimal | Kept | Open-source and secure |

---

## Extensions Removed
1. **PDF Converter Free** – Suspicious source and excessive permissions.
2. **Weather Tab** – Access to browsing history without clear purpose.

---

## How Malicious Extensions Can Harm Users
- **Track browsing habits and steal personal data**
- **Inject ads or redirect search results**
- **Install malware or ransomware**
- **Capture login credentials**

---

## Summary
Removing unnecessary or suspicious extensions can enhance security and improve browser performance. Always install extensions from trusted sources and regularly audit what you’ve installed.

---

## Files Included
- `browser_extension_audit.md` – This report
