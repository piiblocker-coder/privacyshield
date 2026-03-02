# 🔒 PrivacyShield — Protect Your Data in AI Chats

**PrivacyShield** is a Chrome extension that detects and masks personal data before it reaches AI chatbots like ChatGPT and Claude. Your real data never leaves your browser.

🔗 **[Install from Chrome Web Store](https://chromewebstore.google.com/detail/privacyshield/nklghhkmhkmckonncilnaohlihfacoee)** · 🌐 **[Website](https://www.piiblock.com)**

---

## How It Works

1. **Type normally** — Write your prompt as you always do. PrivacyShield highlights personal data it finds in real time.
2. **Review & mask** — Before your message is sent, a dialog shows what was detected. Critical data (credit cards, SSNs, API keys) is auto-protected. You choose what else to mask.
3. **AI gets placeholders** — The AI sees `[PERSON_A]` instead of your real name. When it responds, PrivacyShield swaps the placeholders back so you see your real data — seamlessly.

## What It Detects

| 🔴 Auto-Protected (Critical) | 🟡 You Decide (Soft) |
|---|---|
| Credit Card Numbers | Person Names |
| Social Security Numbers | Addresses |
| API Keys & Secrets | Phone Numbers |
| Passwords | Email Addresses |
| Bank Account Numbers | Dates of Birth |
| | Ages, Salary, Medical Info |

**15+ PII types** detected using regex, NER, and pattern matching.

## Features

- **Real-time detection** — PII highlighted as you type with color-coded underlines
- **Smart masking dialog** — Critical data auto-protected, soft data is your choice
- **Response unmasking** — Placeholders replaced back with your real data in AI responses
- **Right-click mask** — Select any text → "Mask with PrivacyShield" for anything we miss
- **Personal dictionary** — Teach it your name, project codenames, or any custom terms
- **AES-256-GCM encryption** — Mapping data encrypted with ephemeral keys, never written to disk
- **100% local processing** — No servers, no data collection, no analytics
- **Auto-expiring data** — Encrypted mappings expire after 4 hours, purged on browser close

## Supported Sites

- ✅ ChatGPT (chatgpt.com)
- ✅ Claude (claude.ai)
- 🔜 Gemini, Perplexity, Mistral (coming soon)

## Privacy

PrivacyShield processes **all data locally** in your browser. We don't have servers. We don't collect data. There's nothing to breach.

Read our full [Privacy Policy](https://www.piiblock.com/privacy).

---

## 🐛 Bug Reports & Feedback

This repository is the **public issue tracker** for PrivacyShield. We're a small team and every report matters — especially from early users.

### How to Report a Bug

1. **[Open a new issue](../../issues/new)**
2. Include:
   - What you were doing (which site, what action)
   - What happened vs. what you expected
   - Browser version (`chrome://version`)
   - Extension version (shown in the popup header)
   - Console errors if any (`F12` → Console tab → filter for `[PrivacyShield]`)
3. **Never include real PII** in bug reports — use fake data to reproduce the issue

### Feature Requests

Have an idea? [Open an issue](../../issues/new) with the `enhancement` label. We read every one.

### Security Issues

For security vulnerabilities, **do not open a public issue**. Email **security@piiblock.com** directly.

---

## FAQ

**Q: Does PrivacyShield send my data anywhere?**
No. Everything runs locally in your browser. We have no servers and collect no data.

**Q: Why do I see `[PERSON_A]` in the AI's response?**
This means unmasking didn't activate. Try refreshing the page. If the mapping expired (4-hour limit), re-send your prompt with masking enabled.

**Q: Is it free?**
Yes. The free tier includes full detection and masking, forever. Pro (coming soon) adds convenience features like automatic soft-PII masking.

**Q: Can I use this at work?**
Absolutely. PrivacyShield is ideal for anyone using AI with client data, financial info, or proprietary details.

---

## Links

- 🌐 [Website](https://www.piiblock.com)
- 📧 [Support](mailto:support@piiblock.com) — support@piiblock.com
- 🔐 [Security](mailto:security@piiblock.com) — security@piiblock.com
- 📋 [Changelog](https://www.piiblock.com/changelog)

---

© 2026 PiiBlock. All rights reserved.
