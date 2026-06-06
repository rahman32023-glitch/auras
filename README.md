# LOCK — Consistent Character Video

**One image. One identity. Infinite consistent video.**

LOCK is a modern web application that lets you upload a character reference image and generate videos where the **same person** performs dynamic motions (including complex athletic reveals) while maintaining perfect face, body, and identity consistency.

Built for creators who need reliable character consistency in AI video generation.

---

## ✨ Features

### Core Capabilities
- **Character Reference Locking** — Upload one image and keep the exact same face, body, skin tone, and identity across all frames
- **Advanced Consistency Tools**
  - IP-Adapter strength control
  - ControlNet (OpenPose) for precise pose locking
  - AnimateDiff motion modules
- **Multiple AI Providers**
  - Cloud: Kling AI, Runway Gen-3, Luma Dream Machine, Qwen
  - Local: Stable Video Diffusion + AnimateDiff (via ComfyUI)
- **Smart Prompt System**
  - Pre-built athletic reveal prompt
  - One-click style rewrites (Cinematic, Intimate, Editorial)
- **Production-Ready UI**
  - Auto-adaptive controls (IP-Adapter, ControlNet, Motion Module appear only when relevant)
  - Beautiful loading animations
  - Fully responsive + PWA installable on mobile

### Technical Highlights
- Progressive Web App (PWA) with offline support
- Single-file architecture (easy to deploy)
- Vercel-optimized configuration
- Clean, modern dark UI

---

## 🚀 Live Demo

Coming soon — deploy this repo to Vercel to get your own public link.

---

## 🛠 Tech Stack

- **Frontend**: Vanilla HTML + Tailwind CSS + JavaScript
- **PWA**: Service Worker + Web App Manifest
- **AI Integration**: Ready for Kling, Runway, Luma, Qwen + Local ComfyUI workflows
- **Deployment**: Optimized for Vercel

---

## 📦 Getting Started

### Local Use (No installation needed)

1. Download `index.html`
2. Open it in any modern browser
3. Start creating consistent character videos

### Recommended: Deploy to Vercel (Free)

See deployment section below.

---

## 🚀 Deployment

### Deploy to Vercel (Recommended)

1. **Prepare files**
   - Rename `consistent-character-image-to-video-prototype.html` → `index.html`
   - Include the provided `vercel.json`

2. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/lock-consistent-video.git
   git push -u origin main
   ```

3. **Deploy on Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Vercel will automatically use `vercel.json`
   - Click **Deploy**

Your app will be live at `https://your-project.vercel.app`

### Alternative: Netlify Drop (Fastest)

1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `index.html`
3. Get instant public URL

---

## 📋 How to Use

1. **Upload Character Reference** — Drop or select a clear photo of your character
2. **Choose AI Provider** — Click the **API** button (top right)
   - Cloud providers (Kling, Runway, etc.)
   - Local providers (AnimateDiff / Stable Video via ComfyUI)
3. **Adjust Controls** — IP-Adapter, ControlNet, and Motion Module appear automatically for local modes
4. **Generate** — Click "Generate Consistent Video"
5. **Iterate** — Use regenerate or adjust sliders for better results

---

## 🧠 ComfyUI Workflow

A ready-to-import ComfyUI workflow (AnimateDiff + IP-Adapter + ControlNet OpenPose) is included in the conversation history. Import it into ComfyUI for best local results with strong character and pose consistency.

---

## 📁 Project Structure

```
lock-consistent-video/
├── index.html          # Main application (rename from prototype)
├── vercel.json         # Vercel deployment configuration
└── README.md           # This file
```

---

## 🤝 Contributing

This project is open for improvements. Feel free to:
- Add new AI provider integrations
- Improve the ComfyUI workflow
- Enhance mobile experience
- Add new motion presets

---

## 📄 License

MIT License — Free to use and modify.

---

## 💡 Credits

Built as an advanced prototype exploring consistent character video generation using modern AI tools and web technologies.

---

**Made with care for creators who value character consistency.**