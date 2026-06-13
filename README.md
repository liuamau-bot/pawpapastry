# PawPa Pastry — Website

Personal brand website for PawPa Pastry, handmade natural pet cakes & treats, Singapore.

## 🚀 Deploying to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) → Sign in / Sign up
2. Click **New repository**
3. Name it: `pawpapastry` (or `pawpa-pastry`)
4. Set to **Public**
5. Click **Create repository**

### Step 2: Upload Files
1. Click **uploading an existing file**
2. Drag and drop the entire `website/` folder contents (index.html + assets/)
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to **Settings** → **Pages**
2. Under "Source" → select **main** branch → **/ (root)**
3. Click **Save**
4. Your site is live at: `https://yourusername.github.io/pawpapastry`

---

## 🌐 Connecting Your Custom Domain (hosting.com)

### In GitHub:
1. Settings → Pages → **Custom domain**
2. Enter: `www.pawpapastry.com` → Save

### In hosting.com DNS:
Add these records:

| Type  | Name | Value                  |
|-------|------|------------------------|
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | yourusername.github.io |

Wait 24-48 hours for DNS to propagate.

---

## 📁 File Structure

```
website/
├── index.html              ← Main website
└── assets/
    └── images/
        ├── logo/
        │   ├── logo.png    ← Transparent PNG logo
        │   └── logo-full.jpg
        └── products/
            ├── birthday-cupcakes/
            ├── christmas-cupcakes/
            ├── cookies-paws/
            ├── cookies-christmas/
            ├── cookies-dinosaur/
            └── cookies-winnie/
```

---

## 🔮 Future Roadmap

The website is built with future upgrades in mind:

- **E-commerce**: Add Stripe/PayNow checkout by integrating a cart system
- **Membership**: Add login/register pages with a backend (Supabase recommended)
- **CMS**: Add product management via Netlify CMS or Contentful
- **Analytics**: Add Google Analytics 4 by inserting the GA snippet in `<head>`

---

## ✏️ Quick Edits

**Change WhatsApp number**: Search for `6584232193` in index.html and replace

**Add a new product**: Copy a `.product-card` block in index.html and update the content

**Update logo**: Replace `assets/images/logo/logo.png` with your new file (keep same filename)
