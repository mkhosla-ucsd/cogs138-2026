# COGS 138 — Spring 2026 Jekyll Site

This is an adapted Jekyll/Just-the-Docs course website for **COGS 138: Neural Data Science**.

## What was updated

- Quarter metadata changed to **Spring 2026**
- Meeting time changed to **Mondays, Wednesdays, Fridays · 10:00–10:50 AM**
- Course calendar updated for the **Spring 2026** quarter
- Lecture links removed so slides can be added later
- Pages simplified so staff links, Canvas links, and deadlines are easy to update

## Key files to edit

- `_data/sp26/variables.yml` → instructor/staff info, office hours, live course links
- `_data/sp26/course_calendar.csv` → lecture schedule, assignment dates, project dates
- `pages/*.md` → syllabus, assignment text, project instructions, readings page
- `_config.yml` → repository base URL if you rename the repo

## Local development

```bash
bundle install
bundle exec jekyll serve --config _config.yml,_config_dev.yml --destination ./dev-docs
```

Then open the localhost URL shown in the terminal.

## GitHub Pages deployment

This repo includes `.github/workflows/jekyll.yml` so pushing to `main` will build and deploy the site with GitHub Pages.

If your repository is named `cogs138`, the deployed URL will be:

```text
https://mkhosla-ucsd.github.io/cogs138/
```

If you rename the repo, update `baseurl` in `_config.yml`.

## Suggested upload flow

```bash
git init
git branch -M main
git add .
git commit -m "Adapt COGS 138 site for Spring 2026"
git remote add origin https://github.com/mkhosla-ucsd/cogs138.git
git push -u origin main
```
