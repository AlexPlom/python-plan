# Python Path — interactive course tracker

A responsive, static **8-week Python course site** with an interactive dashboard, 56 daily lessons (4 tasks each), 8 projects/milestones, checklists, reflections, resources and a course roadmap.

## Preview locally

Open `index.html` directly in a browser, or run from this directory:

```bash
python -m http.server 8000
```

Visit http://localhost:8000.

## Publish for friends (free)

**Netlify Drop:** Open https://app.netlify.com/drop and drag the `python-path-site` folder into the page. Netlify will provide a public URL you can share. You can optionally configure a custom domain.

**GitHub Pages:** Create a public GitHub repository, upload `index.html`, go to **Settings → Pages → Build and deployment**, and select **Deploy from a branch**, `main`, `/ (root)`.

**Cloudflare Pages:** Create a Pages project and upload this static directory, or connect your Git repository.

## Where progress is stored

Progress and daily notes are saved in each visitor's browser using `localStorage` under `python-path-progress-v1`. Each friend has independent progress within that browser. There are **no accounts, hosted databases or automatic cross-device sync**.

Use **Progress & data → Export progress** to save a JSON backup and **Import progress** to restore it on a different device. Browser data clearance, private mode or a different browser can erase or hide progress.

## Customize

Edit the `raw` array near the bottom of `index.html` to change week topics, projects and milestones. Daily task content is automatically generated from the 56 lesson topics, with a dedicated learn/practice/build/review checklist for each day.

The page uses Google Fonts when online and system fonts as a fallback. The site itself needs no frameworks, bundler or backend.
