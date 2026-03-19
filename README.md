# Battery Stack — AuDHD Energy Tracker

A minimal PWA for tracking your sensory, social, cognitive, and physical energy levels.

## Deploy to GitHub Pages (free, ~5 minutes)

### 1. Create a GitHub repo
- Go to [github.com/new](https://github.com/new)
- Name it `battery-stack` (or whatever you like)
- Make it **Public** (required for free GitHub Pages)
- Click **Create repository**

### 2. Upload files
- Click **"uploading an existing file"** on the empty repo page
- Drag in ALL files from this folder:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Click **Commit changes**

### 3. Enable GitHub Pages
- Go to repo **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Branch: `main`, folder: `/ (root)`
- Click **Save**
- Wait ~60 seconds, your app is live at: `https://YOUR-USERNAME.github.io/battery-stack/`

### 4. Add to iPhone home screen
- Open the URL in **Safari**
- Tap the **Share** button (box with arrow)
- Tap **Add to Home Screen**
- Name it "Batteries" or whatever you prefer
- Done — it now opens full-screen like a native app

## Features
- **4 energy batteries**: Sensory, Social, Cognitive, Physical
- **3 levels each**: Full / Mid / Low
- **Optional notes** for context
- **History view** of all entries
- **14-day trend charts** per battery
- **Week-over-week comparison**
- **Markdown export** (paste into Obsidian)
- **CSV export** for data analysis
- **Offline support** via service worker
- **Data stored locally** on your device (localStorage)

## Data Privacy
All data stays on your device. Nothing is sent to any server.

## Tips
- Log 2-3x per day to spot patterns (morning, afternoon, evening)
- Use notes to capture context: what drained you, what helped
- After 1-2 weeks, check trends to identify your depletion patterns
- Export to Obsidian weekly for your relationship journal integration
