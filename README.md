# 🎸 Guitar Chord Trainer

An interactive, single-file web app for learning and practising guitar chord sequences. No installation required — just open `index.html` in any browser.

## Features

- **5 built-in chord sequences** covering beginner to intermediate level
- **Chord diagrams** showing exact finger positions for every chord
- **Audio playback** — hear each chord strummed through your speakers
- **Adjustable BPM and volume** to practise at your own pace
- **Beat indicator** to keep time visually
- **Custom sequences** — build and save your own using 20+ chords
- **Dark mode** support (follows your system preference)
- **Space bar** shortcut to play / stop

## Chord sequences included

| Sequence | Key | Level |
|---|---|---|
| G – Em – C – D7 | G major | Beginner |
| A – D – E – D | A major | Beginner |
| C – G – Am – F | C major | Beginner–Intermediate |
| Am – F – C – G | A minor | Intermediate |
| D – A – Bm – G | D major | Intermediate (includes Bm barre chord) |

## How to use

1. Click a sequence in the left panel to load it
2. Click any chord card to hear it strummed and see the fingering
3. Hit **Play** (or press **Space**) to loop through the sequence
4. Adjust BPM and Volume with the sliders
5. Click **+ New sequence** to build your own using the chord palette

## Putting it on GitHub Pages

This gives Jamie a permanent link to open the app in any browser — no downloads needed.

### Step 1 — Create a repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** button → **New repository**
3. Name it something like `guitar-chord-trainer`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the file

1. On the new repository page, click **Add file** → **Upload files**
2. Drag and drop `index.html` (and this `README.md` if you like)
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages

1. Go to **Settings** → **Pages** (in the left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: **main**, folder: **/ (root)**
4. Click **Save**

After about 60 seconds, the app will be live at:
```
https://YOUR-USERNAME.github.io/guitar-chord-trainer/
```

That's the URL Jamie can bookmark and open on any device.

---

*Built with vanilla HTML, CSS, and the Web Audio API. No frameworks, no dependencies — just one file.*
