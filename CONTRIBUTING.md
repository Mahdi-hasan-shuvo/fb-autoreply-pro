# 🤝 Contributing to FB AutoReply Pro

Thank you for your interest in contributing to **FB AutoReply Pro** — the #1 Facebook comment auto-reply bot for smart businesses! 🤖

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Branch Naming Convention](#branch-naming-convention)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Contact](#contact)

---

## 📜 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

---

## 💡 How Can I Contribute?

There are many ways to contribute:

- 🐛 **Report bugs** — Found something broken? Open an issue!
- ✨ **Suggest features** — Have a great idea? We'd love to hear it!
- 🔧 **Fix bugs** — Pick an open issue and submit a PR.
- 📖 **Improve documentation** — Fix typos, add examples, clarify steps.
- 🌐 **Add new keyword categories** — Help expand the keyword detection system.
- 🌍 **Add language support** — Bengali, Arabic, Urdu, etc.

---

## 🚀 Getting Started

### 1. Fork the Repository

Click the **Fork** button at the top right of this page.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/fb-autoreply-pro.git
cd fb-autoreply-pro
```

### 3. Install Dependencies

```bash
pip install requests requestssmm
```

### 4. Create a Branch

```bash
git checkout -b feature/your-feature-name
```

### 5. Make Your Changes

Edit code, add features, fix bugs — go for it!

### 6. Test Your Changes

Use **dry-run mode** to safely test without sending real replies:

```bash
# Set dry_run: true in your config before testing
python bot.py
```

### 7. Commit Your Changes

```bash
git add .
git commit -m "feat: add Bengali keyword support for delivery queries"
```

### 8. Push & Open a Pull Request

```bash
git push origin feature/your-feature-name
```

Then open a Pull Request on GitHub.

---

## 🌿 Branch Naming Convention

| Type | Format | Example |
|------|--------|---------|
| New feature | `feature/short-description` | `feature/arabic-keywords` |
| Bug fix | `fix/short-description` | `fix/duplicate-reply-bug` |
| Documentation | `docs/short-description` | `docs/setup-guide-update` |
| Refactor | `refactor/short-description` | `refactor/keyword-engine` |

---

## 🔄 Pull Request Process

1. Make sure your code follows the [Coding Standards](#coding-standards) below.
2. Update the `README.md` if your change introduces new features or changes behavior.
3. Make sure dry-run mode still works correctly.
4. Reference any related issue in your PR description (e.g., `Closes #12`).
5. Your PR will be reviewed by the maintainer within **1–3 business days**.

---

## 🧹 Coding Standards

- **Language:** Python 3.8+
- **Style:** Follow [PEP 8](https://pep8.org/) conventions
- **Comments:** Write clear, helpful inline comments (English preferred)
- **Function Names:** Use `snake_case`
- **Variables:** Use descriptive names — avoid `x`, `tmp`, `data`
- **No hardcoded credentials** — never commit cookies or tokens
- **Dry-run safe:** All new reply actions must respect the `dry_run` flag

### Example Good Commit Messages

```
feat: add spam filter for emoji-only comments
fix: prevent duplicate replies on re-scanned posts
docs: update FAQ with VPS setup instructions
refactor: separate keyword matching into its own module
```

---

## 🐛 Reporting Bugs

When reporting a bug, please include:

- ✅ Your Python version (`python --version`)
- ✅ Operating system (Windows / Linux / Mac / VPS)
- ✅ Steps to reproduce the issue
- ✅ What you expected to happen
- ✅ What actually happened
- ✅ Any error messages or logs (remove sensitive cookie data!)

👉 [Open a Bug Report](https://github.com/Mahdi-hasan-shuvo/fb-autoreply-pro/issues/new?template=bug_report.md)

---

## ✨ Suggesting Features

Have an idea? Tell us:

- What problem does your feature solve?
- How would it work (brief description)?
- Who would benefit from it?

👉 [Open a Feature Request](https://github.com/Mahdi-hasan-shuvo/fb-autoreply-pro/issues/new?template=feature_request.md)

---

## 📩 Contact

For private questions or custom work, reach out directly:

| Channel | Contact |
|---------|---------|
| 📧 Email | shuvobbhh@gmail.com |
| 💬 WhatsApp | +880 1616-397082 |
| 🌐 Portfolio | https://mahdi-hasan-shuvo.github.io/ |

---

**Thank you for helping make FB AutoReply Pro better for thousands of businesses! 🇧🇩❤️**
