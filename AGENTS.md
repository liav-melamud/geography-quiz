# חידון גאוגרפיה — Project Guidelines

## Overview

Interactive Hebrew geography quiz — single-page application.

🔗 **Live site:** https://liav-melamud.github.io/geography-quiz/
📁 **Repository:** https://github.com/liav-melamud/geography-quiz

## Architecture

- Single HTML file (`index.html`) — all CSS and JavaScript are inline, no build step required
- RTL layout (`dir="rtl"`, `lang="he"`)
- Deployed via GitHub Pages from the `main` branch root

## Deployment

```bash
# Push changes to go live
git add .
git commit -m "your message"
git push
```

GitHub Pages auto-deploys from `main` branch. Changes are live within ~1 minute.

## Conventions

- Keep everything in `index.html` — do not split into separate CSS/JS files
- Hebrew text only in UI-facing strings
- Maintain RTL direction throughout
