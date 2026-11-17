# Textoo Portfolio & Play Store Compliance Website

A modern, responsive landing page and privacy policy website for **Textoo** by **Ultronix Studio**, ready for 1-click deployment on **Vercel** or **GitHub Pages**.

## 🚀 Instant Deployment to Vercel

### Option 1: Via GitHub (Recommended)
1. Initialize a new GitHub repository (e.g. `textoo-landing-page`).
2. Push all files from this folder (`Textoo-Website/`) to your repo:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for Textoo website"
   git branch -M main
   git remote add origin https://github.com/<YOUR_USERNAME>/textoo-landing-page.git
   git push -u origin main
   ```
3. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
4. Click **"Add New"** > **"Project"** > Select `textoo-landing-page`.
5. Click **"Deploy"**.
6. In ~15 seconds, Vercel will give you a live production URL:
   - `https://your-project.vercel.app`
   - `https://your-project.vercel.app/privacy` (Your official Google Play Privacy Policy URL!)

---

### Option 2: Via Vercel CLI (Direct from Terminal)
If you have node/npm or vercel installed:
```bash
npm i -g vercel
vercel
```

## 📁 Included Assets
- `index.html`: Hero landing page, feature showcase, dual-SIM explanation, comparison vs chat apps.
- `privacy.html`: Google Play Console compliant Privacy Policy (covering `SEND_SMS`, contact access, and AdMob).
- `vercel.json`: Clean URL routing configuration.
- `assets/`: Hi-res screenshots, transparent mascot logo, and module graphics.
