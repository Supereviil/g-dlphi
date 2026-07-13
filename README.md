# gdlEX: The Windows UI gallery‑dl Should Have Had
gdlEX takes gallery‑dl, wraps it in a proper Windows interface, adds automation and post‑processing, and removes the part where you have to pretend the command line is fun to use.

<img width="811" height="494" alt="Screenshot00" src="https://github.com/user-attachments/assets/5da6fb5f-f3b2-4129-899b-3ab0263cdb93" />

🏛️ Built in Delphi because I don’t want my UI to be a web page cosplaying as an app.

---

## 🧩 What gdlEX Actually Does
gdlEX wraps gallery‑dl in a clean Windows interface and adds an entire ecosystem of features on top:

- Queue management  
- Automation (watch folders, scheduling, cookie rotation)  
- Post‑processing (rename engine, CBZ creation, cleanup)  
- Privacy mode  
- Session tracking  
- Optional integrations (FFmpeg, yt‑dlp, webhooks)

gdlEX is what gallery‑dl looks like after someone who likes Windows apps gets involved.

---

# 🚀 Features Overview
gdlEX operates in two worlds:

1. **gallery‑dl features** — the raw power  
2. **gdlEX-exclusive features** — the quality‑of‑life magic

---

# 1️⃣ Features Powered by gallery‑dl
These are native gallery‑dl capabilities, presented in a way that will make you less prone to self-harm.

### Download Modes
- Single URL  
- Multi‑URL queue  
- Text file input  
- URL‑only extraction  
- Metadata‑only JSON dump  

### Naming & Templates
- Default templates  
- Original filename  
- ID‑only  
- Date + filename  
- Username + ID  
- Category + ID  
- Custom template input  

### Filtering & Rules
- File filter expressions  
- Date before / after  
- File range  
- Min/max size  
- MIME type filtering  

### Network Options
- Retries, timeout, sleep, rate limit  
- Proxy support  
- Custom User-Agent  
- IPv4/IPv6 forcing  
- SSL bypass  

### Authentication
- OAuth  
- API key  
- Browser cookie extraction  
- Cookies.txt rotation  

---

# 2️⃣ gdlEX Companion Features (The Fun Stuff)
These features do **not** exist in gallery‑dl. (The reason you're here)

## 🖥️ UI & Workflow
- Modern Windows UI  
- System tray integration  
- Close-to-tray + notifications  
- Styled output console with privacy filtering that hides your sins
- Session resume  
- Live file-type tally  
- Output trimming   

## ⚙️ Automation Engine
- Watch Folder (auto-import URLs)  
- Daily scheduler  
- Auto-run queue  
- Completion actions:  
  - Open folder  
  - Play sound  
  - Run script  
  - Or do nothing and get on with your life  

## 🧩 Post-Processing
- Remove emoji  
- Remove punctuation  
- Remove spaces  
- Trim filename length  
- Remove custom substring  
- Extension swap (jpeg → jpg, etc.)  
- Rename-on-failure  
- Automatic CBZ creation  
- Empty-folder cleanup  
- Windows-safe path handling  

## 🔄 Session Intelligence
- Files processed  
- CBZ archives created  
- Success/failure state  
- Session receipts  
- Optional logs  
- Download archive support  
- File-type summary  

## 🌐 Integrations
- FFmpeg (optional)  
- yt-dlp fallback  
- Webhook notifications  

## 🔒 Privacy Mode
- Hides sensitive output  
- Redacts URLs and arguments  
- Replaces filenames with a tally  
- Keeps logs clean unless you ask otherwise  

---

# 🪟 Screenshots
*(Something Shiny)*

<img width="811" height="494" alt="Screenshot00" src="https://github.com/user-attachments/assets/a38e18db-2fc8-4483-8340-311580886c08" />
<img width="811" height="494" alt="Settings01" src="https://github.com/user-attachments/assets/c0b25a0f-73ea-4f3c-8a59-4e80d4bb6c2a" />
<img width="811" height="494" alt="Settings02" src="https://github.com/user-attachments/assets/682444ad-de4d-42dd-83f6-895007e1a464" />
<img width="811" height="494" alt="Settings03" src="https://github.com/user-attachments/assets/2f53fec9-cda3-408f-bec8-7c0d814994d9" />
<img width="811" height="494" alt="Settings04" src="https://github.com/user-attachments/assets/a003e12a-f5e6-4cfd-90d7-79bc178c4083" />
<img width="811" height="494" alt="Settings05" src="https://github.com/user-attachments/assets/a1b6d404-fe09-46c0-8e3d-731416ca7680" />
<img width="797" height="487" alt="Settings06" src="https://github.com/user-attachments/assets/fab421aa-b3df-4e37-890e-5e9ab65f2626" />




---

# 📦 Requirements
- A desire to stop babysitting a text file full of command‑line voodoo
- Windows 10 or later (ugh)  
- `gallery-dl.exe` in the same folder as gdlEX  
- Optional:  
  - `ffmpeg.exe`  
  - `yt-dlp.exe`  
  - Cookies.txt or browser profile access  

---

# 📥 Download
Grab the latest release here:  
https://github.com/Supereviil/gdlEX/releases

---

# ❤️ Support Development
If gdlEX saved you time, sanity, or wrist strain:

**Ko‑fi:** https://ko-fi.com/superevil

Every donation goes toward more utilities, more polish, more over‑engineering, and eventually a MacBook Neo for cross‑platform development.

---

# 📄 License
MIT License

---

# 🙌 Credits
- **gallery-dl** by mikf — the powerhouse doing the heavy lifting  
- **gdlEX** by Superevil Enterprises — the companion app, UI, automation, and general bad attitude
