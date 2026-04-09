# 🎂 Mum's Birthday PWA — Deployment Guide

A complete Progressive Web App birthday gift, ready to go live in minutes.

---

## 📁 File Structure

```
birthday-pwa/
├── index.html       ← Main app (all sections, styles, JS)
├── manifest.json    ← PWA manifest (name, icons, theme)
├── sw.js            ← Service worker (offline support)
├── icon-192.png     ← App icon (home screen)
├── icon-512.png     ← App icon (splash screen)
└── README.md        ← This file
```

---

## 🚀 Deploy to Netlify (Easiest — 2 minutes)

### Option A: Drag & Drop (No account needed to start)
1. Go to **https://netlify.com**
2. Sign up free (email or GitHub)
3. Go to your **Sites** dashboard
4. **Drag the entire `birthday-pwa` folder** onto the deploy zone
5. Netlify gives you a live URL instantly (e.g. `https://amazing-mum-abc123.netlify.app`)
6. Optionally click **Site Settings → Change site name** to set a custom slug like `happy-birthday-mum`

### Option B: CLI Deploy
```bash
npm install -g netlify-cli
cd birthday-pwa
netlify deploy --prod --dir .
```

---

## 🚀 Deploy to Vercel (Also 2 minutes)

### Option A: Web Dashboard
1. Go to **https://vercel.com** and sign in (free)
2. Click **Add New → Project**
3. Click **"Upload"** or connect GitHub
4. If uploading: zip the `birthday-pwa` folder, upload it
5. Set **Output Directory** to `.` (the root)
6. Click **Deploy** — done!

### Option B: CLI Deploy
```bash
npm install -g vercel
cd birthday-pwa
vercel --prod
```

---

## 🌐 Deploy to GitHub Pages (Free, permanent)

1. Create a new GitHub repo (e.g. `mums-birthday`)
2. Upload all files from `birthday-pwa/` to the repo root
3. Go to **Settings → Pages**
4. Set Source: **Deploy from branch → main → / (root)**
5. Your URL: `https://yourusername.github.io/mums-birthday`

---

## 📱 How Mum Installs it on Her Phone

### On iPhone (Safari):
1. Open the link in **Safari**
2. Tap the **Share button** (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add** — it appears like a real app icon!

### On Android (Chrome):
1. Open the link in **Chrome**
2. Tap the **three dots menu**
3. Tap **"Add to Home Screen"** or **"Install App"**
4. The app installs and works fully offline

---

## ✅ Checklist Before Sending

- [ ] Deployed and live URL tested
- [ ] Opened on mobile and looks beautiful
- [ ] Tried tapping all 4 Ritual Cards
- [ ] Scrolled through all sections
- [ ] Tested "Add to Home Screen" on phone
- [ ] Sent the link with a loving message 💌

---

## 💌 Suggested Message to Send

> "Mum, I made you something special for your birthday. Open this link — it's all for you. Happy birthday. I love you. ♥"
> 
> [your-link-here]

---

Made with love. ❤️
