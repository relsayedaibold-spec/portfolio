# Ragwa Elsayed — Portfolio

Product & UX · Healthcare Technology. Static site — **every page is fully self-contained**
Product & UX portfolio — healthcare technology. Hand-coded, deployed on Vercel.
(CSS inlined), so it renders correctly whether you open it locally or host it. No build step.
- Responsive landing with hub-and-spoke case studies
- Six enterprise UX case studies (10x Genomics, Natera, Culture Bioscience)
- AIBold product pages (CarePath AI, GlowAI)
- Hand-coded, self-contained pages; deployed on Vercel
## Files
```
index.html                       # landing (overview + compact case cards)
case-chromium-connect.html       # case 01 — 10x Genomics
case-natera-shopfloor.html       # case 02 — Natera
case-natera-uptime.html          # case 03 — Natera
case-natera-accessioning.html    # case 04 — Natera
case-culture-bioscience.html     # case 05 — Culture Bioscience
case-pets-genomics.html          # case 06 — startup
carepath.html · glowai.html      # AIBold product pages (Building Now)
Ragwa_Elsayed_Resume.pdf         # linked by the “Résumé” buttons
assets/ragwa-headshot.jpg        # ⚠ PLACEHOLDER — replace with your real headshot (same filename)
vercel.json · .gitignore
```
No `css/` folder needed — styles are embedded in each page. (Fonts load from Google Fonts, so keep internet on.)

## Before launch
- Replace `assets/ragwa-headshot.jpg` with your real photo (keep the filename).

## To preview locally
Just double-click `index.html`. It now renders fully styled on its own.

## Deploy (GitHub → Vercel)
1. Push all files to a GitHub repo.
2. vercel.com → Add New → Project → Import the repo.
3. Framework preset **Other** (no build). Deploy. `vercel.json` enables clean URLs.
