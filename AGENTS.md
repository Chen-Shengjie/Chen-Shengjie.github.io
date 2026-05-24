# Agent Guidelines

This is Shengjie Chen's personal academic homepage, built with Jekyll and the al-folio theme.

## Local Development

Use Docker for local development when available.

```bash
docker compose up
```

The site runs at `http://localhost:8080`.

## Critical Configuration

When modifying `_config.yml`, keep these deployment settings consistent:

- Personal site: `url: https://chen-shengjie.github.io`
- `baseurl:` should stay empty
- Quote YAML strings with special characters

## Main Content

- `_pages/about.md` controls the homepage.
- `_pages/research.md` controls the research page.
- `_pages/cv.md` links to `CV.pdf`.
- `_bibliography/papers.bib` stores research placeholders and future BibTeX entries.
