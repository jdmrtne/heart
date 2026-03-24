# 💖 I Love You — 360° Love Page

A romantic 3D floating world you can drag around in 360°.  
Powered by pure HTML + Canvas — no frameworks, no installs.

---

## 🖼️ How to Add Your Own Photos

1. Put your photo files inside the **`images/`** folder
2. Open **`index.html`** in a text editor
3. Find this section near the top:

```js
const IMAGE_FILES = [
  'images/photo1.jpg',
  'images/photo2.jpg',
  ...
];
```

4. Replace the filenames with your own, e.g.:

```js
const IMAGE_FILES = [
  'images/us-at-beach.jpg',
  'images/anniversary.jpg',
  'images/selfie.png',
];
```

5. Save and open `index.html` in your browser — done! ✅

> **Supported formats:** JPG, PNG, WEBP, GIF  
> **Tip:** Any number of photos works — the more the merrier!

---

## ✏️ Customize the Text

In `index.html`, find:

```js
const LOVE_TEXT = 'I love you';
```

Change it to any message you want, e.g. `'Te amo'`, `'Forever yours'`, a name, etc.

---

## 🚀 Deploy to GitHub Pages (free hosting)

### Step 1 — Create a GitHub repo

1. Go to [github.com](https://github.com) and sign in
2. Click **+** → **New repository**
3. Name it anything, e.g. `love-page`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload your files

**Option A — Drag & Drop (easiest):**
1. On your new repo page, click **uploading an existing file**
2. Drag the entire `love-site` folder contents:
   - `index.html`
   - `images/` folder with all your photos
3. Click **Commit changes**

**Option B — Git CLI:**
```bash
cd love-site
git init
git add .
git commit -m "my love page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/love-page.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: **main**, folder: **/ (root)**
4. Click **Save**
5. Wait ~1 minute, then your site is live at:

```
https://YOUR_USERNAME.github.io/love-page/
```

---

## 📁 File Structure

```
love-site/
├── index.html       ← main page (edit this)
└── images/
    ├── photo1.jpg   ← replace with your photos
    ├── photo2.jpg
    └── ...
```

---

Made with ❤️
