# Yuanqing Wang — Personal Academic Homepage

My personal academic homepage, hosted on GitHub Pages at
**https://wang-yuanqing.github.io/**.

Based on the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)
template (Jekyll), following the layout of
[tianyu-yang-anna.github.io](https://tianyu-yang-anna.github.io/).

## Deploy to GitHub Pages

1. Create a new GitHub repo named exactly `Wang-Yuanqing.github.io` (must match
   your GitHub username).
2. Push this folder:

   ```bash
   git remote add origin https://github.com/Wang-Yuanqing/Wang-Yuanqing.github.io.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages** → make sure Source is "Deploy from a branch",
   branch `main`, folder `/ (root)`. The site goes live at
   `https://wang-yuanqing.github.io/` after a minute or two.

## Things to customize

- **Profile photo**: replace `images/profile.png` (currently a "Y" placeholder)
  with a real photo, and update `avatar` in `_config.yml` if the filename changes.
- **Main content**: edit `_pages/about.md` — About Me, News, Selected Research,
  Education, Experience, Honors sections all live there.
- **Sidebar info & links**: edit the `author:` block in `_config.yml`
  (bio, email, GitHub, LinkedIn, Google Scholar, etc.).
- **CV**: replace `files/CV_Yuanqing_UTD.pdf` when you update your CV
  (the sidebar CV link points to it via `_config.yml`).
- **Publication teaser images**: drop images into `images/publications/`
  named `dwdpo.png`, `skill-cdpo.png`, `avsg.png`, `heat-field-signatures.png`,
  `croc.png` — cards show "Image pending" until the file exists.
- **Navigation bar**: edit `_data/navigation.yml`.

## Optional: auto-updating Google Scholar citations

Once you have a Google Scholar profile:

1. Find your Scholar ID in your profile URL
   (`https://scholar.google.com/citations?user=SCHOLAR_ID`).
2. In the GitHub repo: **Settings → Secrets and variables → Actions →
   New repository secret**, name `GOOGLE_SCHOLAR_ID`, value = your ID.
3. Enable workflows under the **Actions** tab. The crawler
   (`.github/workflows/google_scholar_crawler.yaml`) runs daily and writes
   citation stats to a `google-scholar-stats` branch.
4. Uncomment the `googlescholar` line in `_config.yml`.

## Optional: analytics & SEO

In `_config.yml`, fill in `google_analytics_id`
([analytics.google.com](https://analytics.google.com/)) and
`google_site_verification`
([Search Console](https://search.google.com/search-console/about)) if wanted.

## Run locally

Requires Ruby + Bundler:

```bash
bundle install
./run_server.sh   # or: bundle exec jekyll serve
```

Then open http://127.0.0.1:4000.
