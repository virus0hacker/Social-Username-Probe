# 🔎 Social Username Probe — OSINT-Lite (Legal)

**Social Username Probe** is a fast and lightweight **public username scanner** that detects whether a username exists across multiple social platforms — using only **public profile pages** with *no login and no private data access*.

> ⚠️ **Legal Notice:** This tool is intended for **educational and ethical OSINT only**.  
> Use only with consent and never to violate privacy or platform Terms of Service.

---

## ✨ Features
- 🚀 High-speed scanning using **parallel threads**
- 🌍 Checks multiple platforms at once
- 🟢 **Color-coded terminal output**
  - Green = Found  
  - Red = Not Found  
  - Yellow = Unknown / Error
- 💾 Export results to **JSON** and **CSV**
- 🖥️ Works on **Windows / macOS / Linux**
- 🔐 No login required — **public data only**

---

## 🌐 Supported Platforms
| Platform     | Supported |
|-------------|-----------|
| Twitter (X) | ✔️ |
| Instagram | ✔️ |
| TikTok | ✔️ |
| YouTube | ✔️ |
| SoundCloud | ✔️ |
| Snapchat | ✔️ |
| Telegram | ✔️ |
| Reddit | ✔️ |
| Facebook | ✔️ |
| GitHub | ✔️ |

---

## 📦 Installation

```bash
git clone https://github.com/USERNAME/social-username-probe
cd social-username-probe
pip install -r requirements.txt

```
Requirements:
```
requests
colorama

```
🖥️ Usage:
```
python social_username_probe.py -u mlftt
```

With extra options:

python social_username_probe.py -u mlftt -t 12 --json result.json --csv result.csv


| Option              | Description                            |
| ------------------- | -------------------------------------- |
| `--username` / `-u` | Username to scan                       |
| `--threads` / `-t`  | Number of parallel threads (default 8) |
| `--json`            | Export results to JSON                 |
| `--csv`             | Export results to CSV                  |

```

🧪 Example Output:

Found      | TikTok        | https://www.tiktok.com/@mlftt
Not Found  | YouTube       | https://www.youtube.com/@mlftt
Found      | SoundCloud    | https://soundcloud.com/mlftt
Unknown    | Telegram      | https://t.me/mlftt

```
📌 Notes:
---
The script does not bypass security systems.

The script does not access any private info.

It only checks publicly available profile URLs.

Some platforms may change layout → results may vary sometimes.

```
🛠️ Add New Platforms:
```
You can easily add more website checks — just edit the SITES section inside the script:
```
{
  "name": "NewSite",
  "url": "https://example.com/{u}",
  "neg": ["not found", "no such user"]
}
```
```
👨‍💻 Developer:
```
```
| Field    | Information                       |
| -------- | ------------------------------    |
| Name     | **virus-hacker**                  |
| Snapchat | **ml-ftt**                        |
| GitHub   | *https://github.com/virus0hacker* |

```
```
📜 License:
```
```
Released under the MIT License — free for legal and ethical use only.
```
```
⭐ Support the Project
```
```
إذا أعجبتك الأداة لا تنس:

ترك نجمة (Star) ⭐ للمستودع

```
