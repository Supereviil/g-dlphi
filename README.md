# gdlEX: The Windows UI gallery‑dl Should Have Had

gdlEX takes gallery‑dl, wraps it in a proper Windows interface, adds automation and a thread-safe post‑processing engine, and removes the part where you have to pretend the command line is fun to use.

<img width="811" height="494" alt="Screenshot00" src="https://github.com/user-attachments/assets/5da6fb5f-f3b2-4129-899b-3ab0263cdb93" />

🏛️ **Built natively in Delphi**—because I don’t want my UI to be a web page cosplaying as an app. 

---

## 🧩 What gdlEX Actually Does
gdlEX wraps gallery‑dl in an ultra-lean Windows interface (using a microscopic 12MB of RAM) and adds an entire ecosystem of companion features:

- **Queue Management** — Full multi-URL queue automation.
- **Automation Engine** — Watch folders for auto-importing, daily scheduling, and smart cookie rotation.
- **Thread-Safe Post‑Processing** — Background filename sanitation, automatic extension swapping, and empty-folder cleanup.
- **Privacy Mode** — Real-time console masking that redacts URLs and file paths on the fly.
- **Comic Archiving** — Automatic sequential folder conversion into standard `.cbz` archives.
- **Integrations** — Native hooks for FFmpeg, yt‑dlp fallbacks, and real-time webhook status notifications.

gdlEX is what gallery‑dl looks like after someone who actually likes native Windows apps gets involved.

---

## 🚀 Features Overview
gdlEX operates in two worlds:
1. **gallery‑dl features** — the raw backend power, exposed gracefully.
2. **gdlEX-exclusive features** — the quality‑of‑life desktop magic.

---

### 1️⃣ Features Powered by gallery‑dl
These are native gallery‑dl capabilities, presented in a way that won't make you want to throw your monitor out a window.

#### Download Modes
* Single URL execution
* Multi‑URL queue tracking
* Text file bulk input (`.txt`, `.lst`, `.url`, `.gdl`, `.csv`)
* URL‑only extraction (simulation testing)
* Metadata‑only raw JSON dumping

#### Naming & Templates
* Default gallery-dl directory hierarchies
* Original source filename preservation
* Unique ID‑only naming
* Date + filename prepending
* Username + ID structures
* Category + ID structures
* Custom string template rule engine

#### Filtering & Rules
* Metadata filter expressions (e.g., `width >= 1920`)
* Strict date range boundaries (before / after constraints)
* Sequential file range clamping
* Min/max file size throttling (in bytes)
* MIME type content filtering

#### Network & Security
* Max retry limits, request timeouts, and native rate-limiting
* Custom user-agent spoofing
* Force IPv4 or IPv6 routing
* Proxy routing configurations
* Insecure SSL certificate validation bypasses

#### Authentication
* Static OAuth bearer tokens
* Dedicated API keys
* Automated browser cookie extraction (Chrome, Edge, Firefox, Brave, Vivaldi, etc.)
* Netscape-format `cookies.txt` file rotation loops

---

### 2️⃣ gdlEX Companion Features (The Fun Stuff)
These features do **not** exist in gallery‑dl. This is the code that saves your sanity.

#### 🖥️ Native UI & Workflow
* Pure Win32 compiled assembly—no Electron, no web runtime, instant start.
* Deep system tray integration with custom task notifications.
* Close-to-tray background execution mode.
* Multi-session crash resilience and automatic job resumption.
* Live file-type count tallying directly in the UI.
* Dynamic terminal output pruning (keeps text buffer lean under massive loops).

#### ⚙️ Automation Engine
* **Active Watch Folders:** Automatically ingests and processes text files dropped into monitored directories.
* **Daily Scheduler:** Set specific times for heavy scraping queues to fire off.
* **Completion Actions:** Trigger a folder opening, play a system alert sound, run a custom cleanup script, or simply do nothing and get on with your life.

#### 🧩 Asynchronous Post-Processing
* **Thread-Isolated Execution:** Heavy I/O processing runs on optimized background threads, keeping the UI perfectly responsive.
* **Filename Sanitation:** One-click removal of emojis, punctuation, symbols, and double spaces.
* **String Scrubbing:** Automatic truncation to custom character limits and mass substring removal.
* **Extension Swapping:** Corrects irregular media containers without messing with file headers (e.g., `jpeg` → `jpg`).
* **Clean Exit Architecture:** Automated post-download verification, empty sub-folder pruning, and Windows-safe path sanitation.

#### 🔄 Session Intelligence
* Live counters tracking total files processed and CBZ archives created.
* Granular success/failure error state evaluation.
* Automated end-of-run Session Receipts and execution logs written straight to output.

---

# 🪟 Screenshots
*(The Shiny Stuff)*

<img width="811" height="494" alt="Screenshot00" src="https://github.com/user-attachments/assets/a38e18db-2fc8-4483-8340-311580886c08" />
<img width="811" height="494" alt="Settings01" src="https://github.com/user-attachments/assets/c0b25a0f-73ea-4f3c-8a59-4e80d4bb6c2a" />
<img width="811" height="494" alt="Settings02" src="https://github.com/user-attachments/assets/682444ad-de4d-42dd-83f6-895007e1a464" />
<img width="811" height="494" alt="Settings03" src="https://github.com/user-attachments/assets/2f53fec9-cda3-408f-bec8-7c0d814994d9" />
<img width="811" height="494" alt="Settings04" src="https://github.com/user-attachments/assets/a003e12a-f5e6-4cfd-90d7-79bc178c4083" />
<img width="811" height="494" alt="Settings05" src="https://github.com/user-attachments/assets/a1b6d404-fe09-46c0-8e3d-731416ca7680" />
<img width="797" height="487" alt="Settings06" src="https://github.com/user-attachments/assets/fab421aa-b3df-4e37-890e-5e9ab65f2626" />

---

# 📦 Requirements & Installation

1. Download gdlEX.
2. Drop `gallery-dl.exe` into the same folder.
3. Stop babysitting a terminal text block.

```text
gdlEX/
├── gdlEX.exe
└── gallery-dl.exe

```

* **OS Support:** Windows 10 or later (ugh).
* **Optional Binaries:** Drop `ffmpeg.exe` or `yt-dlp.exe` in the path if you want post-download conversion or advanced streaming extraction options.

---

# 📥 Download

Grab the latest release here:

https://github.com/Supereviil/gdlEX/releases

---

# ❤️ Support Development

If gdlEX saved you time, sanity, or wrist strain:

**Ko‑fi:** https://ko-fi.com/superevil

Every donation goes toward more utilities, more polish, more over‑engineering, and keeping native desktop tool development alive.

---

# 📄 License

gdlEX is released under the **MIT License**.

---

# 🙌 Credits

* **gallery-dl** by mikf — the powerhouse doing the heavy lifting.
* **gdlEX** by Superevil Enterprises — the companion app, UI, automation, and general bad attitude.
