# socially.kashish — portfolio website

Your complete portfolio site. One file. Free hosting on GitHub Pages.

---

## how to get this live in 10 minutes

### step 1 — create a GitHub account
Go to **github.com** → click Sign Up → use your email → verify it.

### step 2 — create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it exactly: `socially-kashish`
3. Set to **Public** (important — GitHub Pages needs this on the free plan)
4. Leave everything else as default
5. Click **Create repository**

### step 3 — upload the files
1. On your new repo page, click **Add file → Upload files**
2. Drag both files into the box:
   - `index.html` ← your portfolio
   - `README.md` ← this file (optional but good practice)
3. Scroll down → click **Commit changes**

### step 4 — turn on GitHub Pages
1. Click **Settings** (top nav of your repo)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source** → select **Deploy from a branch**
4. Under **Branch** → select **main** → folder stays as `/ (root)`
5. Click **Save**

### step 5 — get your live link
Wait 2 minutes. Refresh the Pages settings page.
Your site will be live at:
```
https://YOURUSERNAME.github.io/socially-kashish/
```
Copy this link → add it to your Instagram bio.

---

## how to edit the site after it's live

You never need to touch code. Just:

1. Download `index.html` from GitHub (click the file → click the download icon)
2. Open it in any text editor:
   - **Windows:** Notepad or Notepad++
   - **Mac:** TextEdit (set to plain text mode) or VS Code (free)
3. Press **Ctrl+F** (or Cmd+F on Mac) to find the text you want to change
4. Make the change → save the file
5. Go back to GitHub → click `index.html` → click the pencil icon (Edit) → paste your new version → Commit

---

## things to personalise before going live

Search for these in `index.html` and replace them:

| find this | replace with |
|---|---|
| `your@email.com` | your real email address |
| `Replace this with your photo` | (see photo instructions below) |
| `50+` (brands grown) | your real number |
| `3×` (enquiry increase) | your real stat |
| `The Personal Stylist` | your real client name or keep generic |
| `YOURUSERNAME` | your actual GitHub username |

---

## how to add your photo

The site currently shows a placeholder with your initial "K". To add your real photo:

1. Take a good headshot photo (square or portrait works best)
2. Rename it `kashish.jpg`
3. Upload it to your GitHub repo (same way you uploaded index.html)
4. In `index.html`, find this line:
   ```
   <div class="about-photo-placeholder">
   ```
5. Replace the entire `<div class="about-photo-placeholder">...</div>` block with:
   ```html
   <img src="kashish.jpg" alt="Kashish — Brand Manager" style="width:100%;height:100%;object-fit:cover;">
   ```

---

## how to connect a custom domain (optional, costs ~₹800/year)

1. Buy a domain from **Namecheap** or **GoDaddy** (e.g. `sociallykashish.com`)
2. In your domain registrar, add these DNS records:
   ```
   Type: A    Name: @    Value: 185.199.108.153
   Type: A    Name: @    Value: 185.199.109.153
   Type: A    Name: @    Value: 185.199.110.153
   Type: A    Name: @    Value: 185.199.111.153
   ```
3. In GitHub → Settings → Pages → Custom domain → type your domain → Save
4. Check **Enforce HTTPS** once it appears
5. Wait up to 24 hours for DNS to propagate

---

## file structure

```
socially-kashish/
├── index.html    ← your entire website (one file)
└── README.md     ← these instructions
```

That's it. One file = one website.

---

Built by Claude for @socially.kashish · 2026
