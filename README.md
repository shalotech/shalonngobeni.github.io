# Shalon Ngobeni — Portfolio

Personal portfolio site built with plain HTML/CSS/JS. Dark, terminal-inspired
design showcasing data science projects, experience, and CV.

## How to host this on GitHub Pages

1. **Create a new repository** on GitHub.
   - Go to github.com → New repository
   - Name it anything, e.g. `portfolio` (or `<your-username>.github.io` if you
     want it at the root of your GitHub domain — see note below)
   - Keep it Public
   - Do NOT initialize with a README (we already have one)

2. **Upload these files** to the repo. Either:
   - Use the GitHub web UI: open the repo → "Add file" → "Upload files" →
     drag in `index.html`, the `cv/` folder, and this `README.md`
   - Or use git from a terminal:
     ```bash
     git init
     git add .
     git commit -m "Initial portfolio site"
     git branch -M main
     git remote add origin https://github.com/<your-username>/<repo-name>.git
     git push -u origin main
     ```

3. **Enable GitHub Pages**:
   - In your repo, go to **Settings → Pages**
   - Under "Build and deployment" → Source, select **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Click **Save**

4. **Wait 1–2 minutes**, then your site will be live at:
   - `https://<your-username>.github.io/<repo-name>/`
   - (or `https://<your-username>.github.io/` if you named the repo
     `<your-username>.github.io`)

## File structure

```
.
├── index.html          # the entire site (HTML + CSS + JS in one file)
├── cv/
│   └── Shalon_Ngobeni_CV_Tech.pdf   # downloadable CV, linked from the site
└── README.md
```

## Updating content later

Everything lives in `index.html`. To update:
- **Projects**: find the `<section id="projects">` block, each project is a
  `.log-entry` div — copy/paste one and edit the text.
- **Experience**: `<section id="experience">`, each role is a `.tl-item` div.
- **CV file**: replace `cv/Shalon_Ngobeni_CV_Tech.pdf` with a new file of the
  same name (or update the `href` links in `index.html` if you rename it).

No build step, no dependencies — just edit and push to `main`, and GitHub
Pages redeploys automatically within a minute or two.
