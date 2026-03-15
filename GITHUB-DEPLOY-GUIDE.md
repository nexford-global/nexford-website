# Nexford Website — GitHub Pages Deploy Guide

## 🚀 Deploy in 5 Minutes (FREE)

### Step 1: Create GitHub Repository
1. Go to https://github.com and sign in (or sign up free)
2. Click the **+** icon → **New repository**
3. Name it: `nexford-website` (or `yourusername.github.io` for a root URL)
4. Set to **Public**
5. Click **Create repository**

### Step 2: Upload the File
1. On your new repository page, click **Add file → Upload files**
2. Drag the `index.html` file onto the upload area
3. Scroll down, write "Initial website upload" in the commit message
4. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. In your repository, click **Settings** (top menu)
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, choose `main` and `/ (root)`
5. Click **Save**

### Step 4: Your Site is Live! 🎉
After 1–2 minutes, your site will be live at:
`https://yourusername.github.io/nexford-website`

---

## 🌐 Connect Your Custom Domain (nexford.co)

1. In GitHub Pages settings, under **Custom domain**, type: `nexford.co`
2. Click **Save**
3. Log into your domain registrar (GoDaddy, Namecheap, etc.)
4. Add these DNS records:
   - Type: A | Name: @ | Value: 185.199.108.153
   - Type: A | Name: @ | Value: 185.199.109.153
   - Type: A | Name: @ | Value: 185.199.110.153
   - Type: A | Name: @ | Value: 185.199.111.153
   - Type: CNAME | Name: www | Value: yourusername.github.io
5. Wait 24–48 hours for DNS propagation
6. Check **Enforce HTTPS** in GitHub Pages settings (free SSL!)

---

## ✏️ How to Update the Website

1. Open `index.html` in any text editor (Notepad, TextEdit, VS Code)
2. Make your changes
3. Go to your GitHub repository
4. Click `index.html` → click the **pencil icon** to edit
5. Paste your updated code
6. Click **Commit changes**
7. GitHub auto-deploys within 60 seconds!

---

## 📄 What's on the Site

| Section | Description |
|---------|-------------|
| Hero | Brand gradient + stats + CTA buttons |
| About | Nexford story + 4 fact cards |
| Services | 6 service cards (01–06) |
| Universities | Full comparison table with 9 universities |
| Process | 5-step enrollment journey |
| Packages | 4 pricing cards (Essential to Elite) |
| Contact | Inquiry form + contact details |
| Footer | Links, social, copyright |

---

## 💡 Tips
- The entire site is **one file** — no database, no server needed
- The contact form currently shows a success message (no backend needed for GitHub Pages)
- To receive real form submissions, sign up at **formspree.io** (free) and replace the form action
- All fonts load from Google Fonts — no local files needed
