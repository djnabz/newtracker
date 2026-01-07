# Push Day - Workout Tracker PWA

A Progressive Web App for tracking Mike Thurston's Push Day workout routine.

## 📱 How to Install on Your Phone

### Option 1: Free Hosting with GitHub Pages (Recommended)

1. **Create a GitHub account** (if you don't have one): https://github.com/signup

2. **Create a new repository**:
   - Go to https://github.com/new
   - Name it `pushday` (or any name you want)
   - Make it **Public**
   - Click "Create repository"

3. **Upload the files**:
   - Click "uploading an existing file"
   - Drag and drop ALL files from this folder:
     - `index.html`
     - `manifest.json`
     - `sw.js`
     - `icon-192.png`
     - `icon-512.png`
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to your repo's **Settings** tab
   - Click **Pages** in the left sidebar
   - Under "Source", select **main** branch
   - Click **Save**
   - Wait 1-2 minutes, then your app will be live at:
     `https://YOUR-USERNAME.github.io/pushday/`

5. **Install on your phone**:
   - Open the URL in Safari (iPhone) or Chrome (Android)
   - **iPhone**: Tap the Share button → "Add to Home Screen"
   - **Android**: Tap the menu (3 dots) → "Add to Home Screen" or "Install App"

### Option 2: Free Hosting with Netlify

1. Go to https://app.netlify.com/drop
2. Drag and drop the entire `workout-pwa` folder
3. Get your free URL instantly
4. Open on phone and install (same as step 5 above)

### Option 3: Free Hosting with Vercel

1. Go to https://vercel.com
2. Sign up with GitHub
3. Import your GitHub repo (if you used Option 1)
4. It deploys automatically
5. Open on phone and install

---

## 🖼️ Creating App Icons

You need two icon files for the app to install properly:
- `icon-192.png` (192x192 pixels)
- `icon-512.png` (512x512 pixels)

### Easy Way - Use the included SVG:
1. Open `icon.svg` in a browser
2. Take a screenshot or use an online converter:
   - https://svgtopng.com/
   - https://cloudconvert.com/svg-to-png
3. Resize to 192x192 and 512x512

### Quick Alternative - Create simple icons:
1. Go to https://favicon.io/favicon-generator/
2. Enter "PD" as text
3. Choose a green background (#a3e635)
4. Download and rename the files

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `index.html` | The complete app (React + Tailwind) |
| `manifest.json` | PWA configuration (app name, icons, colors) |
| `sw.js` | Service Worker for offline support |
| `icon.svg` | Vector icon template |
| `README.md` | This file |

---

## ✨ Features

- ✅ Track all 6 Push Day exercises
- ✅ Log weight and reps for each set
- ✅ View "Last Session" data for progressive overload
- ✅ Add custom exercises
- ✅ Data persists between sessions (localStorage)
- ✅ Works offline after first load
- ✅ Installable on home screen like a native app
- ✅ Dark mode gym aesthetic

---

## 🔧 Troubleshooting

**App won't install?**
- Make sure you're using HTTPS (GitHub Pages provides this)
- Clear your browser cache and try again
- Make sure icon files exist and are named correctly

**Data not saving?**
- Check that localStorage is enabled in your browser
- Some private/incognito modes disable localStorage

**Icons not showing?**
- Make sure `icon-192.png` and `icon-512.png` exist
- Check the file names match exactly (case-sensitive)

---

## 💪 Let's Go!

Time to track those gains. HELL YEA! 🔥
