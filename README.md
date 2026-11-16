# Interest Calculator | వడ్డీ కాలిక్యులేటర్

Simple and compound interest calculator with a step-by-step explanation, in English and Telugu.
Works as a website and can be installed on a phone like an app (PWA). Works offline after the first visit.

## Put it online with GitHub Pages (free)
1. Create a new repository on GitHub (e.g. `interest-calculator`), set to Public.
2. Upload all files in this folder: index.html, manifest.json, sw.js, icon.svg, icon-192.png, icon-512.png.
3. Go to Settings > Pages. Under "Build and deployment", choose Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`. Save.
4. After about a minute your site is live at `https://<your-username>.github.io/interest-calculator/`.

## Install on phone
Open the link in Chrome (Android) > menu (three dots) > "Add to Home screen" / "Install app".
On iPhone: Safari > Share > "Add to Home Screen".

## Formulas used
- Simple interest: SI = P x R x t / 100
- Compound interest: A = P x (1 + R/(100n))^(n x t), CI = A - P
- Time in years: t = years + months/12 + days/365
- Monthly rate is converted to yearly (x 12)
