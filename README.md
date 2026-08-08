# Asad Ullah — Academic Portfolio

Live site (after you publish): `https://YOUR_GITHUB_USERNAME.github.io/`

This folder is a GitHub Pages portfolio in the same jemdoc style as [Muhammad Naeem’s portfolio](https://muhammadnaeem27.github.io/).

## Before you publish

1. **Replace your photo**  
   Put your own headshot at `Figures/photo.png` (square crop works best, ~500×500).

2. **Optional project images**  
   Replace the placeholders in `Figures/` with real screenshots/GIFs if you have them:
   - `building_extraction.png`
   - `uav_simulation.png`
   - `software_apps.png`

3. **Optional edits**  
   Open `index.html` in any editor to update contact info, wording, or links.

## How to publish on GitHub (GitHub Pages)

1. Create a GitHub account (or use your existing one).
2. Create a **new public repository** named exactly:
   ```
   YOUR_GITHUB_USERNAME.github.io
   ```
   Example: if your username is `asadjbutt`, the repo must be `asadjbutt.github.io`.
3. Upload **all files inside this folder** to the repository root (not nested in another folder):
   - `index.html`
   - `jemdoc.css`
   - `LICENSE`
   - `README.md`
   - `Figures/` (with images)
4. In the repo: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`), folder: `/ (root)`
5. Wait 1–2 minutes, then open:
   ```
   https://YOUR_GITHUB_USERNAME.github.io/
   ```

### Upload options

**Option A — GitHub website**  
Upload files via “Add file → Upload files”.

**Option B — Git command line**
```bash
cd Asad_Ullah_Portfolio
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/YOUR_GITHUB_USERNAME.github.io.git
git push -u origin main
```

## Folder contents

```
Asad_Ullah_Portfolio/
├── index.html          # Main portfolio page
├── jemdoc.css          # Site style (same theme as Naeem’s site)
├── LICENSE
├── README.md           # This file
└── Figures/
    ├── photo.png
    ├── building_extraction.png
    ├── uav_simulation.png
    └── software_apps.png
```

## Preview locally

Open `index.html` in a browser, or from this folder run:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.
