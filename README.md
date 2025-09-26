# 🎬 Reels & Shorts Emulator

A web-based **Reels / Shorts Emulator** built with **HTML, TailwindCSS, and vanilla JavaScript**.  
Load your own videos into an **iPhone 14 Pro mockup**, play them like TikTok/Reels/Shorts, and fully customize the experience with the **settings panel**.

---

## 🚀 Features

### 🎥 Video Player
- Load local videos (supports `mp4`, `webm`, `mov`, `mkv`)
- Play / Pause toggle with icons
- Seek timeline with current & total time display
- Next / Previous navigation buttons
- Mute / Unmute toggle
- Mouse **scroll wheel navigation** between videos

### 📱 Device Mockup
- iPhone 14 Pro mockup overlay
- Video aligned inside the mockup
- Adjustable **scale** and **position (X/Y)**
- Upload your own custom mockup image

### ⚙️ Settings Panel
- **Global scale & position** controls  
- **Mockup scale & position** controls  
- **Video container scale & position** controls  
- **Inner video zoom & position** controls  
- **Background customization**  
  - Solid color picker  
  - Gradient mode with 2 colors + direction (linear / radial)  
- **Reset All** button to restore defaults  

👉 **Reminders while using settings:**  
- **Double-click** any slider or number box to reset it to default.  
- **Change folder** anytime from the settings panel.  
- Background can be switched between **solid** and **gradient** mode.  

---

## 🛠️ Tech Stack
- **HTML5** – structure  
- **TailwindCSS** – styling & responsive UI  
- **Vanilla JavaScript** – player logic, controls, settings  

---

## 📂 How to Use
1. Clone or download this repository.  
2. Open `index.html` in a Chromium-based browser (Chrome / Edge).  
   > ⚠️ Folder selection for videos requires Chromium (Firefox & Safari don’t support File System Access API).  
3. Select a folder with videos.  
4. Use the **settings panel** on the right to adjust scale, position, mockup, and background.  
