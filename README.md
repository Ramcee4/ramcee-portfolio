# Modern Developer Portfolio & Showcase

A responsive, high-performance, dark-themed personal website ready for instant 1-click deployment on **Vercel**.

## Features

- **Modern Aesthetic**: Glassmorphism cards, ambient glow gradients, and typography using *Plus Jakarta Sans*.
- **Sections**:
  - Hero with status badge ("Available for work") and call-to-actions
  - Quick statistics & highlights counter
  - Featured projects showcase with tech stack tags and live/code links
  - Categorized tech stack & skills (Frontend, Backend, Cloud & DevOps)
  - Work history & career timeline
  - Interactive contact section with one-click copy email button and form
- **Zero Build Setup**: Pure HTML5, modern Tailwind CSS, and Lucide icons.
- **Vercel Ready**: Includes `vercel.json` with clean URLs and security headers.

---

## How to Deploy to Vercel

### Option 1: Deploy with Vercel CLI (Fastest)

1. Open PowerShell / Command Prompt inside this folder:
   ```bash
   cd "C:\Users\Lenovo\.gemini\antigravity\scratch\vercel-site"
   ```
2. Run:
   ```bash
   npx vercel
   ```
3. Follow the interactive prompts (log in if asked, press Enter for defaults). Your live `.vercel.app` URL will be generated within seconds!

---

### Option 2: Deploy via GitHub (Recommended for automatic updates)

1. Push this folder to a new GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
2. Go to [vercel.com](https://vercel.com) and log in.
3. Click **Add New...** > **Project**.
4. Select your new GitHub repository and click **Deploy**.

---

### Option 3: Local Preview

To test locally in your browser before deploying:
- Double click [index.html](file:///C:/Users/Lenovo/.gemini/antigravity/scratch/vercel-site/index.html) to open directly in Chrome/Edge, or
- Run a quick local server:
  ```bash
  npx serve .
  ```
