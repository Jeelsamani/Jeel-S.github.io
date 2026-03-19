# 🚀 How to Deploy Your Portfolio Live on GitHub Pages

## Step 1 — Create Your GitHub Account (5 minutes)

1. Go to **https://github.com**
2. Click **"Sign up"** (top right)
3. Enter your:
   - Email address
   - A strong password
   - Username — this becomes part of your site URL: `https://YOUR-USERNAME.github.io`
   - **Tip:** Choose a professional username (e.g., `adityasharmadev`, `youfirstname-data`, etc.)
4. Verify your email

---

## Step 2 — Create a New Repository (3 minutes)

1. After logging in, click the **"+"** icon (top right) → **"New repository"**
2. Repository name: **`YOUR-USERNAME.github.io`**
   - ⚠️ This MUST match your GitHub username exactly
   - Example: if your username is `adityasharma`, repo name = `adityasharma.github.io`
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **"Create repository"**

---

## Step 3 — Upload Your Portfolio Files (5 minutes)

**Option A — Upload via browser (easiest, no coding needed):**

1. On your new repository page, click **"uploading an existing file"** link (or drag & drop)
2. Upload ALL of these files at once:
   - `index.html`
   - `style.css`
   - `project-1-velocity.html`
   - `project-2-pricing.html`
   - `project-3-gtm.html`
   - `project-4-dealdna.html`
   - `project-5-weather.html`
   - `project-6-churn.html`
3. Scroll down to **"Commit changes"**
4. Click the green **"Commit changes"** button

**Option B — Using Git (if you install Git):**
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io
# Copy all your files into the cloned folder
cd YOUR-USERNAME.github.io
git add .
git commit -m "Initial portfolio launch"
git push origin main
```

---

## Step 4 — Enable GitHub Pages (2 minutes)

1. In your repository, click **"Settings"** (top menu)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"Deploy from a branch"**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**

---

## Step 5 — Your Site Is Live! 🎉

- Wait **2–5 minutes** for the first deployment
- Visit: **`https://YOUR-USERNAME.github.io`**
- Your 6 project pages are at:
  - `https://YOUR-USERNAME.github.io/project-1-velocity.html`
  - `https://YOUR-USERNAME.github.io/project-2-pricing.html`
  - ... etc.

---

## Step 6 — Personalise Your Site (before sharing)

Open each HTML file in a text editor and replace:

| Find | Replace with |
|------|-------------|
| `YourName` | Your actual name |
| `yourname@email.com` | Your real email |
| `yourusername` | Your GitHub username |
| `yourprofile` | Your LinkedIn profile ID |
| `Ahmedabad, India` | Keep or update your location |

After editing, upload the updated files to GitHub (just drag & drop again in the repo).

---

## Step 7 — (Optional) Add a Custom Domain

If you buy a domain (e.g., `yourname.dev` from Namecheap ~$12/year):

1. In GitHub repo → Settings → Pages → **Custom domain**
2. Enter your domain name and click Save
3. In your domain registrar, add a CNAME record pointing to `YOUR-USERNAME.github.io`

---

## Quick Checklist Before Sharing

- [ ] Name updated in all HTML files
- [ ] Email link updated
- [ ] LinkedIn URL updated  
- [ ] GitHub URLs in each project updated
- [ ] Site loads at `https://YOUR-USERNAME.github.io`
- [ ] All 6 project pages load correctly
- [ ] Navigation links work between pages
- [ ] Mobile view looks good (resize browser window to test)

---

## Updating Your Site Later

Any time you want to update content:
1. Edit the HTML file locally
2. Upload it to GitHub (drag & drop over the old file)
3. Changes go live in ~1 minute

---

## File Structure Reference

```
YOUR-USERNAME.github.io/
├── index.html              ← Main portfolio homepage
├── style.css               ← Shared design system
├── project-1-velocity.html ← DA: Sales Velocity Autopsy
├── project-2-pricing.html  ← DA: Lost Deal Pricing Signal
├── project-3-gtm.html      ← DA: GTM Motion Attribution
├── project-4-dealdna.html  ← DS: Deal DNA Fingerprinting
├── project-5-weather.html  ← DS: Revenue Weather Forecast
└── project-6-churn.html    ← DS: Churn-Expand Predictor
```

---

*Built with Claude · No backend required · Hosted free forever on GitHub Pages*
