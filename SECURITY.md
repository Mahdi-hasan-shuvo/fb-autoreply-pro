# 🔒 Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| v1.x (latest) | ✅ Actively supported |
| < v1.0 | ❌ No longer supported |

---

## 🚨 Reporting a Vulnerability

**Please do NOT report security vulnerabilities through public GitHub Issues.**

If you discover a security vulnerability in **FB AutoReply Pro**, please report it privately so it can be addressed before public disclosure.

### How to Report

Contact the maintainer directly through one of these channels:

| Channel | Contact |
|---------|---------|
| 📧 **Email (Preferred)** | shuvobbhh@gmail.com |
| 💬 **WhatsApp** | +880 1616-397082 |

### What to Include in Your Report

Please provide as much of the following as possible:

- 📋 **Description** of the vulnerability
- 🔁 **Steps to reproduce** the issue
- 💥 **Potential impact** (what could an attacker do?)
- 🛠️ **Suggested fix** (if you have one)
- 🖥️ **Environment details** (OS, Python version, bot version)

### What Happens Next

1. You will receive an acknowledgment within **48 hours**
2. The issue will be investigated and a fix prepared
3. A patched version will be released as quickly as possible
4. You will be credited in the release notes (if you wish)

---

## ⚠️ Important Security Notes for Users

### 🍪 Cookie Security
- **Never share your Facebook session cookies** with anyone
- Store your `cookies.txt` files securely — treat them like passwords
- Do not commit cookies or tokens to any public repository
- Regenerate cookies regularly for safety

### 🔑 Token Security
- Facebook access tokens in config files should never be exposed publicly
- Add `config.jsonc` and any `*.txt` cookie files to your `.gitignore`

### 🤖 Responsible Usage
- Use a scan interval of **30 seconds or more** to avoid triggering Facebook's spam detection
- Do not use this bot to send spam, scam, or misleading messages
- This tool is intended for **legitimate Facebook Business Page owners only**

---

## 🛡️ Scope

Security issues that are **in scope** for reporting:

- Vulnerabilities that could expose user cookies or credentials
- Code injection flaws in the keyword/config parsing system
- Issues that could cause unintended API calls or data leakage

**Out of scope:**

- Issues caused by misconfigured user environments
- Facebook's own platform security issues
- Social engineering attacks

---

*Thank you for helping keep FB AutoReply Pro secure! 🙏*

**— Mahdi Hasan Shuvo | shuvobbhh@gmail.com**
