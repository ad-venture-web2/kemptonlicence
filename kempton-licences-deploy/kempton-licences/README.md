# Q4you Kempton Licences — Website

**Live site:** *(add your Netlify URL here after first deploy)*  
**Client:** Kempton Licences, Glen Marais, Kempton Park  
**Built:** 2026  

---

## 🗂️ Project Structure

```
kempton-licences/
├── index.html        ← Main website (single file, fully self-contained)
├── netlify.toml      ← Netlify deployment config (do not delete)
├── .gitignore        ← Tells Git what to ignore
├── README.md         ← This file — workflow guide
└── assets/           ← Drop any images/logos here when client provides them
```

---

## 🔄 Update Workflow (after initial setup)

When the client gives feedback:

1. **Share feedback with Claude** in a new chat  
   - Paste the specific change request  
   - Claude edits the `index.html` and gives you a new file  

2. **Download the updated `index.html`**

3. **Replace the file in GitHub**  
   - Go to your GitHub repo  
   - Click `index.html` → click the ✏️ pencil (edit) icon  
   - Paste the new content → click **Commit changes**  
   - OR drag-drop the new file onto the repo page  

4. **Netlify auto-deploys in ~30 seconds**  
   - No action needed — Netlify watches GitHub automatically  
   - Share the same URL with the client — it's already updated  

---

## 🛠️ Initial Setup (one time only)

### Step 1 — Create GitHub Repository
1. Go to [github.com](https://github.com) → sign up / log in (free)
2. Click **New repository**
3. Name it: `kempton-licences`
4. Set to **Public** (required for free Netlify)
5. Click **Create repository**
6. Upload all files from this folder (drag & drop onto the repo page)

### Step 2 — Connect Netlify
1. Go to [netlify.com](https://netlify.com) → sign up with GitHub (free)
2. Click **Add new site → Import an existing project**
3. Choose **GitHub** → select `kempton-licences` repo
4. Build settings: leave everything blank (already configured in netlify.toml)
5. Click **Deploy site**
6. Netlify gives you a URL like `https://kempton-licences.netlify.app`
7. **Optional:** rename it under Site Settings → Site name

### Step 3 — Note your URL
Paste it at the top of this README under "Live site" and share with the client.

---

## 📋 Client Feedback Log

Use this section to track requested changes:

| Date | Feedback | Status |
|------|----------|--------|
| -    | Initial build | ✅ Done |

---

## 🎨 Brand Reference

| Element | Value |
|---------|-------|
| Primary gradient | Purple `#3d2b7a` → Teal `#1a6b5a` |
| Teal | `#1a6b5a` |
| Purple | `#3d2b7a` |
| Green (people icons) | `#2e7d32` |
| Font — Headings | Playfair Display (serif, italic) |
| Font — Logo | Cormorant Garamond (serif, italic) |
| Font — Body | DM Sans |
| Logo concept | Q4you — large Q with 4you inside, three person icons |
| Tagline | "We Handle Your Vehicle Licensing So You Don't Have To" |

---

## 📞 Client Contact Details (on site)

- **Address:** 37B Mona Street, Glen Marais, Kempton Park  
- **WhatsApp/Call:** 084 264 2299 | 082 783 4657  
- **Email:** kempton.licences@gmail.com  
