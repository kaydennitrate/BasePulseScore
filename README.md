# BasePulseScore

**BasePulseScore** — a simple, mobile-first on-chain activity checker for the **Base Network**. Instantly calculate and visualize a wallet's on-chain score based on transaction activity, NFT holdings, and DeFi interactions. Built as a static site (HTML/CSS/JS) with TailwindCSS and feather icons; integrates with OnchainKit when ready.

---

## Live Demo
(Deploy to Vercel or your preferred static host. Example: `https://your-project.vercel.app`)

---

## Features
- Paste a Base/EVM wallet address and get an instant on-chain score
- Mobile-first UI built with TailwindCSS
- Animated score display and descriptions for score ranges
- Clean header and info section explaining what an on-chain score is
- Footer with ENS credit, Twitter link, and donation/tips buttons
- Easy to replace mock score function with OnchainKit / backend integration

---

## Quick Start (upload / deploy on mobile)
1. Create a new GitHub repository (e.g. `BasePulseScore`) and upload the site files (index.html, any assets, etc.).  
2. Sign in to Vercel (mobile browser is fine) and choose **Import Project** → connect your GitHub account → select the repository.  
3. Use default build settings for a static site. Click **Deploy**.  
4. Optionally, add environment variables or replace the mock score function with your OnchainKit API later.

---

## Local Dev (if you use Termux / Cloud IDE)
If you prefer to test locally in a cloud IDE or Termux (mobile):
```bash
# optional, for Termux / cloud shell
pkg install nodejs git     # Termux: only if needed
git clone https://github.com/<your-username>/BasePulseScore.git
cd BasePulseScore
# No build step for static HTML; open index.html in a previewer or push to Vercel
