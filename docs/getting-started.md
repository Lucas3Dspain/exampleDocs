# Getting Started

Welcome! This guide will help you get started with your MkDocs documentation site.

## Quick Start

1. **Clone this repository**
   ```bash
   git clone https://github.com/lucas3dspain/exampleDocs.git
   cd exampleDocs
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Preview locally**
   ```bash
   mkdocs serve
   ```
   Open http://127.0.0.1:8000 in your browser.

4. **Start writing**
   - Edit files in the `docs/` directory
   - Update `mkdocs.yml` to add pages to navigation
   - Commit and push to deploy!

## Project Structure

```
exampleDocs/
├── docs/                    # Your documentation pages
│   ├── index.md            # Home page
│   ├── getting-started.md  # This file
│   └── examples.md         # Markdown examples
├── .github/
│   └── workflows/
│       └── ci.yml          # GitHub Actions workflow
├── mkdocs.yml              # MkDocs configuration
├── requirements.txt        # Python dependencies
└── README.md                # Project README
```

## Customization

### Change Site Name

Edit `mkdocs.yml`:
```yaml
site_name: Your Site Name
```

### Add Pages

1. Create a new `.md` file in `docs/`
2. Add it to the `nav` section in `mkdocs.yml`:
   ```yaml
   nav:
     - Home: index.md
     - Getting Started: getting-started.md
     - Your New Page: your-new-page.md
   ```

### Change Theme Colors

Edit the `palette` section in `mkdocs.yml`:
```yaml
palette:
  - scheme: default
    primary: blue  # Change this
    accent: blue   # Change this
```

## Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch.

To enable GitHub Pages:

1. Go to your repository Settings
2. Navigate to Pages
3. Select "GitHub Actions" as the source

Your site will be available at:
`https://yourusername.github.io/exampleDocs/`

## Need Help?

- Check out the [Examples](examples.md) page to see all available features
- Read the [MkDocs Documentation](https://www.mkdocs.org/)
- Browse [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

