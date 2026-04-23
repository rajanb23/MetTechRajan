# MedTech Pulse — U.S. Healthcare Technology Explorer

An interactive web application exploring U.S. medical technology trends, underfunded healthcare areas, innovation pipelines, and market dynamics. Built for researchers, policy interns, and anyone working at the intersection of science and healthcare policy.

🔗 **[View Live Site](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

---

## What's Inside

- **Technologies** — Explore 12 health technology sectors with toggleable filters by sector, readiness level, and equity reach. Click any card for a full breakdown of what the technology does, what health problem it solves, and the policy angle.
- **Underfunded Frontiers** — Deep dives into 5 underinvested areas: Mental Health, Maternal Health, Rare Disease, Climate Health, and Indigenous/Tribal Health.
- **Market Dynamics** — 5 interactive lenses covering FDA approval pathways, reimbursement logic, the Valley of Death, platform effects, and the equity gap.
- **Innovation Pipeline** — A live pipeline from basic discovery to FDA approval, with spotlight filters by disease area (Cancer, Mental Health, Rare Disease, Chronic, Infectious Disease).

---

## Deployment (GitHub Pages)

### Option 1 — Deploy from `docs/` folder

1. Create a `docs/` folder in your repository
2. Place `medtech_explorer.html` inside it and rename it `index.html`
3. Go to your repo → **Settings** → **Pages**
4. Under **Build and deployment**, set source to **Deploy from a branch**
5. Set branch to `main` and folder to `/docs`
6. Click **Save** — your site will be live in ~2 minutes

### Option 2 — Deploy from root

1. Place `medtech_explorer.html` at the root of your repo and rename it `index.html`
2. Go to your repo → **Settings** → **Pages**
3. Set source to **Deploy from a branch**, branch `main`, folder `/ (root)`
4. Click **Save**

---

## File Structure

```
your-repo/
├── docs/
│   └── index.html        ← the medtech_explorer.html file renamed
└── README.md
```

---

## Built With

- Vanilla HTML, CSS, JavaScript — no framework, no build step
- [Chart.js](https://www.chartjs.org/) — pipeline and funding charts
- [Google Fonts](https://fonts.google.com/) — Playfair Display, Space Grotesk, Space Mono
- Data sourced from NIH, FDA, CMS, ARPA-H (FY2024)

---

## Local Development

No build step needed. Just open the file directly in a browser:

```bash
open docs/index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/docs/
```

---

*Built for NIH sustainable healthcare investment research · FY2024*
