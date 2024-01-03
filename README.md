# Aandsliv Website

Website for aandsliv.dk and åndsliv.dk

## Add new post (for writers)

Add a file in the directory `src/_posts/`.
It must have the format `YYYY-MM-DD-<TITLE>.md`.
E.g., `2024-01-03-the-meaning-of-life.md`.

Additionally, the file must begin with
```md
---
author: First name Last name
abstract: Article abstract here...
subsection: section name
---

```

Note that `subsection` can have the following values:
- `tidsskrift`
- `politik-og-samfund`
- `kultur`
- `indsendelser`

## Build

1. Install jekyll
2. Run `cd src/`
3. Run `jekyll serve`
