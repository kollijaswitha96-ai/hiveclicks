# ⚡ HiveClicks Digital Marketing Agency Website

A high-converting, modern digital marketing agency website & landing page suite built for **HiveClicks**. 

Designed to be hosted 100% free on **GitHub Pages** so you can immediately share live, lightning-fast links with your prospective leads.

---

## 🚀 Live Pages Included

1. **`index.html`** — The Main Digital Marketing Agency Landing Page:
   - High-contrast Hero section with clear value proposition and social proof.
   - Comprehensive breakdown of services (Google Ads, Meta/Social Ads, SEO, Conversion Rate Optimization, Analytics).
   - **Interactive Growth & ROI Calculator** (leads can slide ad budgets and see projected returns).
   - Case studies with hard metrics (ROAS, CPA reduction, revenue growth).
   - 4-step agency workflow blueprint.
   - Full Lead Capture / Audit Booking Form with budget and bottleneck filters.
   - Trust-building FAQ accordion and floating quick-contact button.

2. **`audit.html`** — Dedicated 1-Click Free Growth & SEO Audit Teardown Page:
   - Streamlined, distraction-free page tailored for cold outreach, email blasts, and direct pitch links.

---

## 🌐 How to Publish on GitHub in 3 Minutes (Free)

### Method A: Direct Upload via GitHub Web (Zero Coding / Zero Installation)

1. **Log in to GitHub**: Go to [github.com](https://github.com) (sign up for free if you don't have an account).
2. **Create a New Repository**:
   - Click the **`+`** icon in the top-right corner and select **"New repository"**.
   - Name your repository (e.g., `hiveclicks` or `agency`).
   - Choose **Public**.
   - Check **"Add a README file"** (or leave it unchecked).
   - Click **"Create repository"**.
3. **Upload the Website Files**:
   - In your new repository, click **"Add file"** &rarr; **"Upload files"**.
   - Drag and drop `index.html` and `audit.html` from `C:\Users\hp\.gemini\antigravity\scratch\hiveclicks-website\`.
   - Click **"Commit changes"**.
4. **Enable GitHub Pages**:
   - In your repository, click **Settings** (tab at the top right).
   - On the left sidebar menu, click **Pages**.
   - Under **"Build and deployment" &rarr; "Branch"**:
     - Select **`main`** (or `master`) branch.
     - Folder: select **`/ (root)`**.
     - Click **Save**.
5. **Get Your Live Link**:
   - Wait 30–60 seconds, then refresh the page.
   - GitHub will display your live public URL:
     - **Main Site:** `https://<your-username>.github.io/hiveclicks/`
     - **Audit Landing Page:** `https://<your-username>.github.io/hiveclicks/audit.html`

---

### Method B: Using GitHub Desktop or Git CLI

If you use GitHub Desktop:
1. Open GitHub Desktop and click **File &rarr; New Repository** or **Add Local Repository**.
2. Select the folder `C:\Users\hp\.gemini\antigravity\scratch\hiveclicks-website`.
3. Click **Publish repository** to push it to your GitHub profile.
4. Go to repository **Settings &rarr; Pages** and select the `main` branch.

---

## 📩 Connecting the Lead Form to Your Email / WhatsApp

Currently, the forms simulate successful submission. To receive lead submissions directly into your inbox or CRM:

### Option 1: Free Formspree / Web3Forms (Takes 1 minute)
1. Sign up at [formspree.io](https://formspree.io) or [web3forms.com](https://web3forms.com).
2. Get your unique endpoint URL.
3. In `index.html`, update the `<form>` tag:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="space-y-6">
   ```
Every time a lead submits the form, you will receive an instant email notification.

### Option 2: Direct WhatsApp Click-to-Chat
Change the floating button or CTA button link to:
```html
https://wa.me/YOUR_PHONE_NUMBER?text=Hi%20HiveClicks,%20I'd%20like%20to%20request%20a%20marketing%20audit.
```

---

## 🏷️ Using a Custom Domain (Optional)

If you own `hiveclicks.com` or `growth.hiveclicks.com`:
1. In your GitHub Repository, go to **Settings &rarr; Pages**.
2. Under **Custom domain**, enter your domain name (e.g. `hiveclicks.com`).
3. Point your DNS CNAME / A records to GitHub Pages as guided in the GitHub Pages settings.
