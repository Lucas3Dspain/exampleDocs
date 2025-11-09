# exampleDocs

A minimal GitHub Pages documentation site built with MkDocs and Material theme.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-blue)](https://lucas3dspain.github.io/exampleDocs/)
[![MkDocs](https://img.shields.io/badge/MkDocs-Material-green)](https://squidfunk.github.io/mkdocs-material/)

## Setup

This repository uses MkDocs with the Material theme to generate documentation and automatically deploys to GitHub Pages via GitHub Actions.

## Local Development

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Serve the documentation locally:
   ```bash
   mkdocs serve
   ```

3. Build the documentation:
   ```bash
   mkdocs build
   ```

## Deployment

The documentation is automatically deployed to GitHub Pages when you push to the `main` branch. The GitHub Actions workflow (`.github/workflows/ci.yml`) handles the build and deployment process.

## Project Structure

```
.
├── docs/                      # Markdown documentation files
│   ├── index.md              # Home page
│   ├── getting-started.md    # Getting started guide
│   ├── examples.md           # Markdown examples
│   └── assets/               # Images, favicons, etc.
│       └── favicon.svg       # Site favicon
├── .github/
│   └── workflows/
│       └── ci.yml           # GitHub Actions workflow
├── mkdocs.yml                # MkDocs configuration
├── requirements.txt          # Python dependencies
├── LICENSE                   # MIT License
├── CONTRIBUTING.md          # Contribution guidelines
└── README.md                # This file
```

## Adding Content

1. Add or edit Markdown files in the `docs/` directory
2. Update the `nav` section in `mkdocs.yml` to include new pages
3. Commit and push your changes

## Resources

- [MkDocs Documentation](https://www.mkdocs.org/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
