# Åndsliv Website

Website source for [Åndsliv.dk](https://xn--ndsliv-hua.dk/).

## Add new post (for writers)

Add a file in the directory `src/_posts/`.
It must have the format `YYYY-MM-DD-<TITLE>.md`.
E.g., `2024-01-03-the-meaning-of-life.md`.
This will be both the link and the title shown on the page.

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

## Build

1. Install jekyll
2. Run `cd src/`
3. Run `jekyll serve`
