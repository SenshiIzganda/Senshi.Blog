# SENSHI.BLOG — স্থপতির কলম

A bold magazine-style blog built for GitHub Pages. No backend, no database — pure HTML/CSS/JS.

## Features
- ✅ Bold Magazine Design
- ✅ Dark / Light Mode Toggle
- ✅ English + Bangla Language Switch
- ✅ Write & Publish Blog Posts
- ✅ Search Posts
- ✅ Categories & Tags
- ✅ Real-time Clock, Date, IP Address Display
- ✅ Share Posts
- ✅ Posts saved in localStorage (persists across sessions)
- ✅ Fully responsive (mobile friendly)
- ✅ Zero dependencies — pure HTML/CSS/JS

## Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to github.com
2. Click **New Repository**
3. Name it: `yourusername.github.io` (for main site)
   OR any name like `blog` (for project site)
4. Set to **Public**
5. Click **Create Repository**

### Step 2: Upload Files
1. Click **Add file → Upload files**
2. Upload `index.html`
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** → **/ (root)**
4. Click **Save**

### Step 4: Access Your Blog
- Main site: `https://yourusername.github.io`
- Project site: `https://yourusername.github.io/blog`

**Live in 2-5 minutes!** 🚀

## Customize

### Change Blog Name
In `index.html`, find:
```
SENSHI<span>.</span>BLOG
```
Replace with your name.

### Change Author Name
Find all instances of `'Senshi'` and replace with your name.

### Add More Categories
Find `filterCategory` in the nav and add new ones.

## Note on Posts
Posts are saved in browser's localStorage.
Each visitor sees only their own posts + the default sample posts.
For a shared blog with a real database, you'd need a backend service.
