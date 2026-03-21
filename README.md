# 🔒 PiiBlocker — Protect Your Data in AI Chats

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/nklghhkmhkmckonncilnaohlihfacoee?label=Chrome%20Web%20Store)](https://chromewebstore.google.com/detail/privacyshield/nklghhkmhkmckonncilnaohlihfacoee)

**PiiBlocker by PiiBlock** is a free Chrome extension that detects and masks personally identifiable information (PII) before it reaches AI chatbots like ChatGPT, Claude, and Gemini. It uses a combination of NER-based detection and regex pattern matching, running 100% locally in the browser with zero data collection. Your real data never leaves your device.

🔗 **[Install from Chrome Web Store](https://chromewebstore.google.com/detail/privacyshield/nklghhkmhkmckonncilnaohlihfacoee)** · 🌐 **[Website](https://www.piiblock.com)**
▶️ **[Watch the 60-second demo](https://www.youtube.com/watch?v=VpYqkC-_UVg)**
---

## How It Works

1. **Type normally** — Write your prompt as you always do. PiiBlocker highlights personal data it finds in real time.
2. **Review & mask** — Before your message is sent, a dialog shows what was detected. Critical data (credit cards, SSNs, API keys) is auto-protected. You choose what else to mask.
3. **AI gets placeholders** — The AI sees `[PERSON_A]` instead of your real name. When it responds, PiiBlocker swaps the placeholders back so you see your real data seamlessly.

## Why PiiBlocker?

Every day, millions of people paste sensitive personal data into AI chatbots without realizing that data is stored, potentially used for model training, and at risk of exposure through data breaches. Enterprise DLP tools exist but cost hundreds per month and require IT teams to deploy.

PiiBlocker provides equivalent protection for free, running entirely in the browser with zero infrastructure. PiiBlock does not operate any servers and cannot access user data by design.

## What It Detects

| 🔴 Auto-Protected (Critical) | 🟡 You Decide (Soft) |
| --- | --- |
| Credit Card Numbers | Person Names |
| Social Security Numbers | Addresses |
| API Keys & Secrets | Phone Numbers |
| Passwords | Email Addresses |
| Bank Account Numbers | Dates of Birth |
| | Ages, Salary, Medical Info |
| | UK National Insurance Numbers |

**15+ PII types** detected using regex, NER, and pattern matching.

## Features

* **Real-time detection** — PII highlighted as you type with color-coded underlines
* **Smart masking dialog** — Critical data auto-protected, soft data is your choice
* **Response unmasking** — Placeholders replaced back with your real data in AI responses
* **Right-click mask** — Select any text → "Mask with PiiBlocker" for anything we miss
* **Personal dictionary** — Teach it your name, project codenames, or any custom terms
* **AES-256-GCM encryption** — Mapping data encrypted with ephemeral keys, never written to disk
* **100% local processing** — No servers, no data collection, no analytics
* **Auto-expiring data** — Encrypted mappings expire after 4 hours, purged on browser close

## Supported Sites

* ✅ ChatGPT (chatgpt.com)
* ✅ Claude (claude.ai)
* ✅ Gemini (gemini.google.com)

More platforms coming with Pro.

## Privacy

PiiBlocker processes **all data locally** in your browser. PiiBlock does not operate any servers and cannot access your data by design. There is no telemetry, no analytics, no cookies, and no third-party scripts. There's nothing to breach.

Read our full [Privacy Policy](https://www.piiblock.com/privacy).

---

## 🐛 Bug Reports & Feedback

This repository is the **public issue tracker** for PiiBlocker. We're a small team and every report matters — especially from early users.

### How to Report a Bug

1. **[Open a new issue](https://github.com/piiblocker-coder/privacyshield/issues/new)**
2. Include:
   * What you were doing (which site, what action)
   * What happened vs. what you expected
   * Browser version (`chrome://version`)
   * Extension version (shown in the popup header)
   * Console errors if any (`F12` → Console tab → filter for `[PiiBlocker]`)
3. **Never include real PII** in bug reports — use fake data to reproduce the issue

### Feature Requests

Have an idea? [Open an issue](https://github.com/piiblocker-coder/privacyshield/issues/new) with the `enhancement` label. We read every one.

### Security Issues

For security vulnerabilities, **do not open a public issue**. Email **[security@piiblock.com](mailto:security@piiblock.com)** directly.

---

## FAQ

**Q: Does PiiBlocker send my data anywhere?**
No. Everything runs locally in your browser. PiiBlock does not operate any servers and collects no data.

**Q: Why do I see `[PERSON_A]` in the AI's response?**
This means unmasking didn't activate. Try refreshing the page. If the mapping expired (4-hour limit), re-send your prompt with masking enabled.

**Q: Is it free?**
Yes. The free tier includes full detection and masking for ChatGPT, Claude, and Gemini — forever, with no usage limits and no account required. Pro (coming soon at $4.99/month) adds convenience features like fully automatic soft-PII masking, smart masking strategies, and a privacy dashboard.

**Q: Can I use this at work?**
Absolutely. PiiBlocker is designed for anyone who uses AI chatbots with real data — freelancers, students, doctors, lawyers, developers, and enterprise employees. Because all processing happens locally with zero data collection, it can help organizations maintain GDPR and data protection compliance when employees use AI tools.

---

## Links

* 🌐 [Website](https://www.piiblock.com)
* 🛒 [Chrome Web Store](https://chromewebstore.google.com/detail/privacyshield/nklghhkmhkmckonncilnaohlihfacoee)
* ▶️ [Demo Video](https://www.youtube.com/watch?v=VpYqkC-_UVg)
* 𝕏 [Twitter/X](https://x.com/PIIBlocker)
* 💼 [LinkedIn](https://www.linkedin.com/company/piiblock)
* 📧 [Support](mailto:support@piiblock.com) — support@piiblock.com
* 🔐 [Security](mailto:security@piiblock.com) — security@piiblock.com
* 📋 [Changelog](https://www.piiblock.com/changelog)

---

© 2026 PiiBlock. All rights reserved.
