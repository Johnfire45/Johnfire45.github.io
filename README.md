# RedSpire Security — johnfire45.github.io

GitHub Pages backend for RedSpire Security — Cybersecurity Consulting for Startups, SaaS & Growing Businesses.

**Public website:** https://redspiresecurity.com/
**Founded by:** Harshit Shah · Cybersecurity Consultant

## Live URLs

| URL | Content |
|---|---|
| https://redspiresecurity.com/ | RedSpire Security website (primary, via CNAME) |
| https://johnfire45.github.io/ | GitHub Pages backend |
| https://johnfire45.github.io/portfolio/ | Old portfolio (preserved) |

## Repo structure

```
/
├── index.html        ← Consulting website homepage
├── styles.css        ← Consulting website CSS
├── assets/           ← Images, icons (currently empty — pending favicon/OG card)
├── portfolio/        ← Old portfolio (kept intact, not modified)
├── favicon.ico
├── robots.txt
└── LICENSE
```

## Consulting website

Built with plain HTML, CSS, and minimal vanilla JS. No frameworks, no build step.

**Services:** Security Audit & VAPT · Secure Code Review · Cybersecurity Advisory

**Contact:** hsharshit4545@gmail.com · [LinkedIn](https://www.linkedin.com/in/harshit-shah-699a54127/)

Source files are maintained at `Consultation-firm/website-v1/` in a separate working directory. Copy updated files to this repo root to redeploy.

## Deploying updates

```bash
# Copy updated files from the working directory
cp ~/Documents/Consultation-firm/website-v1/index.html ./index.html
cp ~/Documents/Consultation-firm/website-v1/styles.css ./styles.css

# Commit and push
git add index.html styles.css
git commit -m "Update consulting website"
git push origin main
```

GitHub Pages deploys automatically on push to `main`. Live within ~2 minutes.

## Restoring the portfolio

The old portfolio is preserved in `portfolio/` and accessible at `/portfolio/`. It has not been modified.

If you need to restore it to root: `git checkout backup/portfolio-original`.
