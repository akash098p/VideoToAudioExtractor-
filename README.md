# 🎵 Video Audio Trimmer

A modern, fully **client-side web application** to extract, trim, preview, and download audio from video files — directly in the browser.  
No uploads. No server. No data tracking. 🚀

---

## ✨ Features

- 🎬 Upload video or audio files (Drag & Drop supported)
- 🎧 Extract audio directly from video
- ✂️ Trim audio using:
  - Interactive waveform
  - Draggable trim handles
  - Start & End sliders
- ▶️ Live preview of trimmed audio
- 💾 Download trimmed audio
- 🎼 Output format selection (WAV, MP3*, OGG*)
- 📱 Fully responsive & mobile-friendly UI
- 🔒 100% client-side — your files never leave your device

> ⚠️ MP3 & OGG export currently download as WAV due to browser limitations.  
> True MP3/OGG encoding requires additional libraries (e.g. `lamejs`).

---

## 🖥️ Live Preview 

https://akash098p.github.io/VideoToAudioExtractor/

## 📂 Supported Input Formats

Most modern browsers support:

- MP4
- WebM
- MOV
- AVI
- MKV
- FLV
- OGG  
- and many more (browser-dependent)

---

## 🛠️ Built With

- **HTML5**
- **CSS3** (modern gradients & animations)
- **Vanilla JavaScript**
- **Web Audio API**
- **OfflineAudioContext**
- **Canvas API** (waveform rendering)

No frameworks. No dependencies.

---

## 🚀 How to Use

1. Open the app in your browser
2. Upload or drag & drop a video file
3. Wait for the waveform to load
4. Adjust start & end trim points
5. Click **Preview Trim**
6. Click **Download Audio**

That’s it ✅

---

## 📦 Installation

No installation required.

### Option 1: Run locally
```bash
git clone https://akash098p.github.io/VideoToAudioExtractor.git
cd VideoToAudioExtractor 
open index.html
