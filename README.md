# 🎬 YouTube WatchNLearn (MVP Demo)

A Chrome Extension that pauses YouTube videos at key timestamps and shows **interactive learning activities** — quizzes, reflections, sliders, and budget allocations — right inside the video player.

---

## ✨ Features
- ⏸️ **Auto-pause** at defined timestamps  
- 📝 **Quizzes & Reflections** for comprehension checks  
- 📊 **Sliders & Budget allocations** for interactive exercises  
- ✅ **Progress tracking** with insight chips  
- 🎨 **Branded overlay UI** with logo, tags, and visual polish  

---

## 🚀 Getting Started

### 1. Download the demo build
👉 [Download youtube-overlay-extension-branded.zip](https://github.com/freakish23/WatchNLearn)

### 2. Load the extension in Chrome
1. Unzip the downloaded file.  
2. Open `chrome://extensions/` in Chrome.  
3. Enable **Developer mode** (top-right).  
4. Click **Load unpacked** and select the unzipped folder.  

### 3. Try it on demo videos
- [Opportunity Cost](https://www.youtube.com/watch?v=uorrlWJ23Mg) (activities at 60s, 120s, 180s, 240s)  
- [Supply & Demand](https://www.youtube.com/watch?v=B9MPklfyRHI) (activities at 45s, 120s, 180s)  

The video will pause automatically at checkpoints and display an overlay activity card.  

---

## 📂 Project Structure
youtube-overlay-extension-branded/
│── manifest.json # Extension manifest (MV3)
│── content.js # Content script, injects overlay + monitors video
│── overlay.html # Overlay container UI
│── overlay-ui.js # Overlay logic & activity renderers
│── styles.css # Local CSS styling
│── activities.json # Activity definitions (timestamps, prompts, options)
│── logo.png # Placeholder logo (swap with your brand)
│── background.js # Minimal service worker



---

## 🛠 Customization
- **Add new activities** → edit `activities.json`  
- **Change branding** → replace `logo.png` and tweak `styles.css`  
- **Add activity types** → extend `overlay-ui.js`  

---

## 🧪 Demo Screenshots
*(Replace with actual screenshots from your overlay)*
<img width="1440" height="699" alt="Screenshot 2025-09-05 at 6 37 02 PM" src="https://github.com/user-attachments/assets/fc63ea62-0c3b-4811-84ae-a820ca2eafbb" />

---

## 🔒 Privacy
- All data is stored **locally in Chrome storage**.  
- No data is sent to external servers.  

---

## 📜 License
MIT License © 2025 [bhargav]

