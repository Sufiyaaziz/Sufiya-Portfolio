# Sufiya Aziz — Portfolio

Personal portfolio site for Sufiya Aziz — Software Developer / Full-Stack / Data Analyst.

**Live site (Claude artifact):** https://claude.ai/artifact/Hz1m1AAh71fZDnQAhNnnkH

## What's inside

A single self-contained `index.html` — no build step, no dependencies to install.
Everything (styles, scripts, certificate images, and the résumé PDF) is inlined into that
one file, so it runs anywhere you open or host it.

Sections: Hero · AI Tools · Skills · Certifications (with certificate viewer) · Projects ·
Experience · Education · Contact.

Features: light/dark theme toggle (saved across visits), scroll progress bar, typed-role
animation, animated stat counters, certificate viewer modal with zoom, mobile nav drawer,
and a "Download résumé" button.

## Running it locally

No build tools needed. Either:

- Double-click `index.html` to open it in a browser, or
- Serve it locally for a cleaner experience (fixes some browsers' restrictions on local files):

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying with GitHub Pages

1. Push this repo to GitHub (see commands below).
2. On GitHub: **Settings → Pages → Source → Deploy from a branch → `main` / `/ (root)`**.
3. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a
   minute or two.

## Pushing this folder to GitHub from VS Code

1. Open this folder in VS Code (`File → Open Folder…`).
2. Open a terminal in VS Code (`` Ctrl+` ``) and run:

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Or use VS Code's built-in Source Control panel (the branch icon on the left sidebar) —
it will prompt you to initialize the repo and publish it to GitHub with a few clicks,
no terminal needed.

## Editing

Open `index.html` in VS Code and edit directly — all CSS is in a `<style>` block and all
JavaScript in a `<script>` block near the bottom of the same file.

## Credits

- Certificates: Simplilearn SkillUp (Microsoft Power BI, Microsoft Excel) and Excelerate
  (Saint Louis University, RIT Tiger STRIPES Program)
- Fonts: Outfit & Inter via Google Fonts
