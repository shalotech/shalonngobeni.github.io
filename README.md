# Shalon Ngobeni — Portfolio

🔗 **Live site:** [shalotech.github.io](https://shalotech.github.io/)

A personal portfolio site for Shalon Thlarihani Ngobeni — Data Science
student showcasing machine learning, data engineering, and analytics
projects. Built with plain HTML/CSS/JS (no frameworks, no build step), styled
with a dark, terminal-inspired aesthetic.

## About

I'm a Data Science student based in Johannesburg, working through the
ALX/ExploreAI Academy programme and holding a UCT Data Science with Python
certificate. This site brings together my projects, experience, and CV in
one place.

**Core stack:** Python · SQL · Pandas · scikit-learn · LightGBM · AWS ·
Terraform · Tableau · Git · Docker

## What's on the site

- **About** — background and current focus
- **Projects** — AWS fraud detection lakehouse, Nedbank Zindi ML challenge,
  Maji Ndogo data pipeline, Mutiny x ALX analytics assessment, Forest Walk
  analytics, and a commission tracker app for Phambili Butchery and Grill
- **Experience** — work history across data, quality control, and
  operations roles
- **Contact** — email, phone, and a downloadable CV

## File structure

```
.
├── index.html                       # the entire site (HTML + CSS + JS)
├── cv/
│   └── Shalon_Ngobeni_CV_Tech.pdf   # downloadable CV
└── README.md
```

## Updating content

Everything lives in `index.html`, no build process required:

- **Projects** — find `<section id="projects">`; each project is a
  `.log-entry` div. Copy one and edit the text to add a new project.
- **Experience** — find `<section id="experience">`; each role is a
  `.tl-item` div.
- **CV** — replace `cv/Shalon_Ngobeni_CV_Tech.pdf` with an updated file of
  the same name, or update the `href` links in `index.html` if renamed.

Push changes to `main` and GitHub Pages redeploys automatically, usually
within a minute or two.

## Hosting

This repo is configured for GitHub Pages, deploying from the `main` branch
at the root. Settings → Pages → Source: Deploy from a branch → `main` /
`/ (root)`.

---

Built with HTML, CSS, and a fair amount of curiosity.
