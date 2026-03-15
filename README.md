# danielwilkins.dev

Personal site — IT Operations leadership portfolio.

## Deploy to GitHub Pages

1. Create a new repo (e.g., `danielwilkins.dev` or `portfolio`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages → Source** → select `main` branch, root folder
4. Site will be live at `https://<username>.github.io/<repo-name>` within ~60 seconds

## Custom Domain (danielwilkins.dev)

The `CNAME` file is already included. After enabling Pages:

1. In your domain registrar's DNS settings, add:
   - **A records** pointing to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **CNAME record**: `www` → `<username>.github.io`
2. In GitHub repo **Settings → Pages → Custom domain**, enter `danielwilkins.dev`
3. Check "Enforce HTTPS" once DNS propagates (can take up to 24 hours)

## Structure

```
├── index.html          # About / Home
├── resume.html         # Expanded resume (full version)
├── philosophy.html     # Build Your World leadership framework
├── case-studies.html   # Project deep dives
├── style.css           # IBM Plex + Atlassian palette design system
├── script.js           # Scroll-triggered fade animations
├── CNAME               # GitHub Pages custom domain config
└── README.md
```

## Stack

- Pure HTML/CSS/JS — no build step, no frameworks
- IBM Plex Sans + IBM Plex Mono (Google Fonts)
- Atlassian Design System color palette
- Responsive down to 640px

## To Update

Edit HTML files directly. No build process needed. Push to main and GitHub Pages deploys automatically.
