# What's Not Working? 🔧

A dead-simple tech troubleshooting app built for non-technical users. Tap a device, pick a problem, follow illustrated step-by-step fixes.

## Features
- 5 devices: Apple TV, Wi-Fi, iPhone/iPad, Ring Camera, Nest Thermostat
- Custom SVG product illustrations on every step
- Large text, high contrast, mobile-first
- "Call your son" fallback 😄
- Works offline (PWA)
- Installable on iPhone/Android home screen

---

## 📁 Project Structure

```
whats-not-working/
├── index.html          ← The entire app (single file)
├── public/
│   ├── manifest.json   ← PWA install config
│   └── sw.js           ← Offline service worker
├── firebase.json       ← Firebase Hosting config
├── vercel.json         ← Vercel deployment config
├── package.json
├── .gitignore
└── README.md
```
