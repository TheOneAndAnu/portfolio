# Anubhuti Khare — Portfolio Site

> Technical Writer · API & Developer Docs · SaaS Products

Live at: `https://[your-username].github.io/portfolio/`

---

## 🗂️ File Structure

```
portfolio/
├── index.html              ← Main portfolio page (hero, about, skills, experience, writing, cats)
├── resume.html             ← Printable résumé page
├── tools/
│   ├── api-explorer.html   ← Interactive API Docs Explorer
│   ├── style-linter.html   ← Style Guide Linter
│   ├── changelog-gen.html  ← Changelog Generator
│   └── writer-checklist.html ← Tech Writer Pre-publish Checklist
└── README.md
```

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Name it `portfolio` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload Your Files

**Option A: GitHub Web UI (easiest)**
1. In your new repo, click **Add file → Upload files**
2. Drag and drop all the files, keeping the folder structure:
   - `index.html` → root
   - `resume.html` → root
   - `tools/` folder with all 4 HTML files inside
3. Click **Commit changes**

**Option B: Git CLI**
```bash
git init
git add .
git commit -m "Initial portfolio deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Select branch: `main`, folder: `/ (root)`
6. Click **Save**

### Step 4 — Your site is live! 🎉

After ~2 minutes, your site will be at:
```
https://YOUR_USERNAME.github.io/portfolio/
```

---

## 🧪 Tools Overview

| Tool | File | What it does |
|------|------|--------------|
| API Docs Explorer | `tools/api-explorer.html` | Interactive mock API browser with live request simulation |
| Style Guide Linter | `tools/style-linter.html` | Checks for passive voice, jargon, weak phrases, long sentences |
| Changelog Generator | `tools/changelog-gen.html` | Turns raw dev notes into formatted Markdown changelogs |
| Writer Checklist | `tools/writer-checklist.html` | Pre-publish quality checklist with progress tracking |

---

## 🐱 Easter Eggs

- **Konami Code** on any page: `↑ ↑ ↓ ↓ ← → ← → B A` — triggers a secret Rosa message
- **Click the nav logo 5 times** — unlocks a hint about the Konami code
- Rosa approves all content.

---

## 🎨 Customization

All colors are defined as CSS variables at the top of `index.html`:

```css
:root {
  --saffron: #f4720b;    /* Primary accent */
  --marigold: #f9c01e;   /* Secondary accent */
  --rose: #e8456a;       /* Highlight */
  --teal: #0d9488;       /* Info/links */
  --lavender: #8b5cf6;   /* Poetry section */
}
```

To update your contact links, search for `khareanu1612@gmail.com` and `anubhuti-khare-83a843195` in `index.html`.

---

## 📝 License

Personal portfolio — not for redistribution. Content (poems, writing) © Anubhuti Khare.
