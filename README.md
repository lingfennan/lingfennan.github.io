# lingfennan.github.io

Personal academic homepage of Ruian Duan (段瑞安), Assistant Professor, Department of
Computer Science and Technology, Tsinghua University.

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll template and deployed via GitHub Actions (see `.github/workflows/jekyll.yml`).
The site is served at <https://lingfennan.github.io>.

## Editing the content

All content is plain Markdown/YAML — no coding required. After editing, commit and push;
GitHub Actions rebuilds and deploys automatically (usually within a couple of minutes).

| What | Where |
|------|-------|
| Bio, research summary, recruiting blurb, **News** | `_pages/about.md` |
| Site title, name, email, social links, avatar | `_config.yml` (the `author:` block) |
| Top navigation menu | `_data/navigation.yml` |
| Publications (one file per paper) | `_publications/YYYY-MM-DD-slug.md` |
| Patents | `_pages/patents.md` |
| Talks (one file per talk) | `_talks/YYYY-MM-DD-slug.md` |
| Teaching / courses | `_pages/teaching.html` and `_teaching/` |
| Projects | `_portfolio/*.md` |
| CV page | `_pages/cv.md` (on-page CV; no downloadable PDF is published) |
| Profile photo | `images/profile.jpg` |
| PDFs | papers in `files/papers/`, patents in `files/patents/`, legacy in `publications/` |

### Add a news item
Edit the `News` section at the bottom of `_pages/about.md`. One bullet per item, newest on top.

### Add a publication
Create `_publications/YYYY-MM-DD-slug.md` copying the front matter of an existing one.
Put the PDF in `files/papers/` and set `paperurl` to it (omit `paperurl` if there is no PDF).
`category: conferences` or `category: manuscripts` controls the grouping on the Publications page.

### Add a patent
Add a bullet in the appropriate section of `_pages/patents.md`; drop the PDF in `files/patents/`
and link it as `[[PDF]](/files/patents/<file>.pdf)`.

## TODO (fill in when available)
- Set your Tsinghua email in `_config.yml` (`author.email`) once active; it currently shows your Gmail.
- Optional: add `author.orcid` / Semantic Scholar in `_config.yml` if you create those profiles.
- Optional: publish a clean CV PDF at `files/cv.pdf` (without a personal phone number) and restore the link in `_pages/cv.md`.
- Add a Tsinghua office/contact block and teaching/course content as they become available.

## Local preview (optional)
Requires Ruby ≥ 3.0, or Docker. With Docker Desktop running:

```bash
docker compose up        # serves at http://localhost:4000
```

The previous frameset-based site is preserved under `_archive/` for reference.
