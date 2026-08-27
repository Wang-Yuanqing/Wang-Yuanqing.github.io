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

- **Profile photo**: replace `images/wyq.jpeg` with a new photo, and update
  `avatar` in `_config.yml` if the filename changes.
- **Main content**: edit `_pages/about.md` — About Me, News, Publications,
  Education, and Experience sections all live there.
- **Sidebar info & links**: edit the `author:` block in `_config.yml`
  (bio, email, GitHub, LinkedIn, etc.).
- **CV**: replace `files/CV_Yuanqing.pdf` when you update your CV
  (the sidebar CV link points to it via `_config.yml`).
- **Publication teaser images**: drop images into `images/publications/`
  named `dwdpo.jpg`, `skill-cdpo.png`, `avsg.jpg`, `heat-field-signatures.jpg` —
  cards show "Image pending" until the file exists.
- **Navigation bar**: edit `_data/navigation.yml`.

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
