# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML site hosted on GitHub Pages at `https://datenkeller.github.io`. No build step, framework, or package manager is used — files are served as-is by GitHub Pages.

## Local Development

Open HTML files directly in a browser, or serve them with any static file server:

```sh
python3 -m http.server 8000
```

## Deployment

Pushing to the `master` branch automatically publishes the site via GitHub Pages.

## Repository Structure

- `index.html` — main landing page
- `tubs_extern/pubs.hmtl` — external publications page (note: filename typo `.hmtl`, preserve it to avoid breaking existing links)
