
#  Phishing Email Analysis Report

# Email Summary

**Subject:** Urgent: Unusual Activity Detected on Your Account  
**From:** PayPal Security Team <security@paypal-alert.com>  
**Message:** Claims account is restricted and requests immediate verification through a fake link.

---

## 🔍 Identified Phishing Indicators

### 1. Spoofed Email Address
- `security@paypal-alert.com` is not an official PayPal domain.

### 2. Suspicious Link
- Displayed: https://paypal.com...
- Actual: https://paypal.com.verify-info-login-security.tk
- `.tk` domains are often free and abused by scammers.

### 3. Urgent Language
- “Failure to verify within 24 hours will result in permanent suspension.” — creates panic.

### 4. Generic Greeting
- Uses “Dear Customer” — real emails use your actual name.

### 5. Grammar and Formatting Issues
- Inconsistent signature format.
- Phrases like “verify-info-login” are suspicious.

---

##  Summary Table

| No. | Indicator             | Details                                                  |
|-----|------------------------|----------------------------------------------------------|
| 1   | Spoofed Email          | Looks like PayPal but isn't.                            |
| 2   | Mismatched URL         | Link shown != real destination                          |
| 3   | Threatening Language   | Tries to scare user into fast reaction                  |
| 4   | Generic Greeting       | No user personalization                                 |
| 5   | Formatting & Grammar   | Low-quality text, signature, and strange URLs           |

---

## Recommended Folder Structure

```
phishing-email-analysis-task/
├── phishing_email_sample.txt
├── phishing_analysis_report.md
└── README.md
```
