# Ehsan Shareghi's academic homepage

This site uses the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
template (a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme).

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

## Structure

- `_config.yml` — site-wide settings (title, author, social links).
- `_pages/about.md` — landing page (Bio, Research Areas, News, Future Students).
- `_pages/people.md` — current students and alumni.
- `_pages/cv.md` — short CV with a link to the full PDF.
- `_pages/publications.html` / `_pages/teaching.html` — auto-generated index pages.
- `_publications/` — one Markdown file per paper (categorised as `notes`, `selected`, or `conferences`).
- `_teaching/` — one file per course.
- `files/` — PDFs (publications, slides, CV).
- `images/` — profile photo and assets.

## Deploying

Push to `https://github.com/eehsan/eehsan.github.io` on `main`. GitHub Pages
will build automatically.
