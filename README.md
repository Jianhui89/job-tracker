# Job Application Tracker

A personal job application tracker built with vanilla HTML/JS. Data stored in browser localStorage. AI gap analysis powered by Claude.

**Live app:** https://jianhui89.github.io/job-tracker

---

## Deploy to GitHub Pages (one-time setup)

### Step 1 — Create the repo

1. Go to https://github.com/new
2. Repository name: `job-tracker`
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Upload the file

1. In the new repo, click **Add file → Upload files**
2. Drag and drop `index.html`
3. Commit message: `Initial commit`
4. Click **Commit changes**

### Step 3 — Enable GitHub Pages

1. Go to **Settings → Pages** (left sidebar)
2. Under **Source**, select `Deploy from a branch`
3. Branch: `main` / `root`
4. Click **Save**

### Step 4 — Access your app

Wait ~60 seconds, then visit:
```
https://jianhui89.github.io/job-tracker
```

---

## Features

- **Board view** — kanban across 6 statuses (Wishlist → Offer/Rejected)
- **List view** — sortable table with all fields
- **Timeline view** — chronological sorted by applied date
- **AI gap analysis** — paste a JD, click analyse, get a tailored gap analysis using your profile
- **CSV export** — download all applications as a spreadsheet
- **Dark mode** — auto-detects system preference

## Data

All data is stored in your browser's `localStorage` under the key `jat_v2`. It persists across page refreshes but is browser-local — not synced across devices.

To back up: use the **Export CSV** button.

## Future upgrades

- [ ] Google Drive sync for cross-device persistence
- [ ] Interview notes timeline per application
- [ ] Reminder / follow-up date alerts
- [ ] Tag system for role types
