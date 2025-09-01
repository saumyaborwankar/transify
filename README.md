# Real-Time Audio Transcript Extension

A Chrome extension that captures audio directly from browser tabs and transcribes it in real time, displayed in a clean, user-friendly side panel.

## DEMO
[Watch the demo](demo/transify-demo.mp4)

## 🎯 Features

### Core

- **Real-time Audio Capture** – Record audio from any active browser tab
- **Live Transcription** – Instant transcription with auto-scrolling
- **Multiple API Providers** – Works with Google Speech-to-Text, OpenAI Whisper, Deepgram, and Fireworks
- **Professional UI** – Clean side panel interface for easy use
- **Export Options** – Copy text to clipboard or download transcripts as TXT, JSON, or SRT
- **Session Timer** – Track how long you’ve been recording
- **Auto-scroll** – Always see the latest transcript line

### Advanced

- **Multi-provider Fallback** – Automatically switch providers if one fails
- **Offline Buffering** – Audio buffering during connection issues
- **Error Handling** – Clear, user-friendly messages
- **Keyboard Shortcuts** – Toggle recording with Ctrl/Cmd + Enter
- **Easy Configuration** – Manage API keys and provider settings from the panel

---

## 🚀 Installation

### Development Setup

1. Open Chrome and go to `chrome://extensions/`
2. Enable **Developer mode** (top right)
3. Click **Load unpacked** and select the extension folder

### Production Setup

1. Download the extension ZIP file
2. Extract it
3. Load it into Chrome via **Load unpacked** (or install from Chrome Web Store when available)

---

## 🔧 API Configuration

The extension supports four transcription providers:

1. **Google Cloud Speech-to-Text**

   - Free tier, accurate, supports streaming
   - Setup: Create a project in Google Cloud Console → Enable API → Generate API key

2. **OpenAI Whisper API**

   - High accuracy, supports multiple languages
   - Setup: Create an account → Enable billing → Generate API key

3. **Deepgram(RECOMMENDED)**

   - Real-time streaming with multiple models
   - Setup: Create an account → Generate API key

4. **Fireworks API**
   - Fast processing, competitive pricing
   - Setup: Create an account → Generate API key

**Configuration Steps**

- Open side panel → Click settings (⚙️) → Select provider → Enter API key → Save

---

## 📖 Usage

1. **Start Recording**

   - Open the side panel → Click **Start Recording**
   - Play audio in the tab you want to capture

2. **View Transcript**

   - Live transcript appears with timestamps
   - Auto-scroll keeps the newest lines visible

3. **Stop Recording**

   - Click **Stop Recording**
   - Timer stops, session ends

4. **Export Transcript**
   - Click 📥 to open export options
   - Save as TXT, JSON, SRT, or copy to clipboard

### Shortcuts

- Ctrl/Cmd + Enter → Toggle recording
- Escape → Close export modal

---

## 🏗️ Architecture
