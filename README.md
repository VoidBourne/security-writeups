# Security Writeups

This repo documents my hands-on learning as I work toward a career in penetration testing — lab writeups, machine walkthroughs, and exercises, kept here as evidence of progress.

## About

I'm currently building foundational offensive security skills through structured labs (Hack The Box and TCM Security)

**Certifications:** SC-900, Google Professional Cybersecurity Certificate
**Learning path:** TCM Security (Practical Ethical Hacking Course)

## Writeups

### Hack The Box

| Machine | Difficulty | Skill area | Writeup |
|---|---|---|---|
| Dancing | Easy | SMB enumeration | [`htb/dancing-smb`](./htb/dancing-smb) |
| Reactor | Easy | 
|Cap | Easy | Linux privesc | [`htb/cap`](./htb/cap) |

### TCM Security

| Lab | Topic | Writeup |
|---|---|---|
| Authentication 0x01 | Brute-force login (no rate limiting) | [`tcm/auth-0x01-brute-force`](./tcm/auth-0x01-brute-force) |
| Authentication 0x02 | MFA bypass via parameter tampering | [`tcm/auth-0x02-mfa-bypass`](./tcm/auth-0x02-mfa-bypass) |

## Writeup format

HTB machine writeups follow a consistent walkthrough structure:

1. **Overview** : what the box teaches, difficulty
2. **Reconnaissance** : initial scanning/enumeration
3. **Enumeration / Exploitation** : the walkthrough itself
4. **Flag / Result** : outcome (flags redacted where required)
5. **Takeaways** : what I learned and why it matters

TCM Security labs are written as professional-style pentest reports instead, since that's the format the course teaches:

1. **Executive Summary** : the finding, in plain terms
2. **Scope & Methodology**
3. **Finding** : severity, description, impact
4. **Steps to Reproduce**
5. **Remediation**
6. **References** (CWE, etc.)

---
*Flags are redacted.*
