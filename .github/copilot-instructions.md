# 生信爱好者周刊 (Bioinformatics Weekly)
Chinese bioinformatics weekly publication built with MkDocs. A documentation site containing 170+ weekly issues covering bioinformatics topics, research, tools, and career insights.

Always reference these instructions first and fallback to search or bash commands only when you encounter unexpected information that does not match the info here.

## Working Effectively
- Bootstrap, build, and test the repository:
  - `python3 --version` -- ensure Python 3.12+ is available
  - `pip3 install -r requirements.txt` -- takes 30-60 seconds. NEVER CANCEL.
  - `mkdocs build --clean` -- takes 5 seconds consistently. NEVER CANCEL. Set timeout to 30+ seconds.
  - `mkdocs serve --dev-addr=0.0.0.0:8000` -- serves at http://localhost:8000/weekly/

- Build validation:
  - Build generates warnings about RSS plugin options (non-blocking, expected)
  - Build warnings about external links in issue-41.md and issue-61.md (non-blocking, expected)
  - Site builds successfully in ~5 seconds with 170+ HTML pages
  - Generated files: RSS feeds, search index, sitemap, all issue pages

- Development server:
  - Run `mkdocs serve --dev-addr=0.0.0.0:8000` to start development server
  - Access at http://localhost:8000/weekly/
  - Supports live reloading when content changes
  - Server startup takes ~5 seconds

## Validation
- Always test the complete build-serve-navigate cycle after making changes.
- ALWAYS verify these core scenarios manually:
  1. Main page loads: `curl -s "http://localhost:8000/weekly/" | grep -o "<title>.*</title>"`
  2. Individual issues load: `curl -s "http://localhost:8000/weekly/issue-1/" | grep -o "<title>.*</title>"`
  3. Search functionality is present: Check for search input in rendered HTML
  4. RSS feeds generate: `curl -s "http://localhost:8000/weekly/feed_rss_created.xml" | head -5`
  5. Navigation links work: Check issue links in main page HTML

- Build artifacts are in `site/` directory -- this is automatically excluded from Git via .gitignore
- Do not commit build artifacts (`site/` and `.cache/` directories)

## Common Tasks

### Building the Documentation
```bash
# Clean build (recommended)
mkdocs build --clean  # Takes ~5 seconds

# Incremental build
mkdocs build  # Takes ~3-4 seconds

# Strict mode (will fail due to RSS plugin warnings - expected)
mkdocs build --strict  # DO NOT USE - has known warnings
```

### Development Server
```bash
# Start development server
mkdocs serve --dev-addr=0.0.0.0:8000

# Access the site
curl http://localhost:8000/weekly/
# Or browse to http://localhost:8000/weekly/
```

### GitHub Pages Deployment
```bash
# Deploy to GitHub Pages (requires repo permissions)
mkdocs gh-deploy --clean
```

### Content Structure
```
issues/              # All weekly issue content (issue-1.md through issue-171.md)
├── issue-1.md      # First issue: "生信是什么"
├── issue-2.md      # 生信的境界与道路
├── ...
└── issue-171.md    # Latest issue

mkdocs.yml          # MkDocs configuration
requirements.txt    # Python dependencies
overrides/          # Custom theme overrides
├── main.html       # Custom HTML template
└── partials/       # Template partials
```

### Repository Information
- **Language**: Primarily Chinese content with some English technical terms
- **Content Type**: Weekly articles about bioinformatics, research, career advice
- **Site URL**: https://openbiox.github.io/weekly/
- **Build System**: MkDocs with Material theme
- **Deployment**: GitHub Actions workflow (jekyll-gh-pages.yml)

### Python Dependencies (requirements.txt)
- mkdocs: Core documentation generator
- mkdocs-material: Material Design theme
- mkdocs-rss-plugin: RSS feed generation
- mkdocs-git-revision-date-plugin: Git-based page dates
- mkdocs-with-pdf: PDF generation capability

### Expected Build Timing
- **NEVER CANCEL**: All commands complete quickly but set appropriate timeouts
- Dependency installation: 30-60 seconds (set timeout to 120+ seconds)
- Clean build: 5 seconds (set timeout to 30+ seconds)
- Development server startup: 5 seconds (set timeout to 30+ seconds)
- No tests to run - this is a content/documentation repository

### Known Issues and Warnings
- RSS plugin warnings about deprecated options (as_creation, as_update) - non-blocking
- External link warnings in issue-41.md and issue-61.md - non-blocking
- Strict mode build fails due to above warnings - do not use strict mode
- Build creates 170+ HTML files which is expected

### Frequently Used Commands Output Reference

#### Repository Root Structure
```bash
$ ls -la
.github/            # GitHub workflows and configurations
.gitignore          # Excludes site/, .cache/, .DS_Store
README.md           # Repository documentation in Chinese
free/               # Free resources directory
image/              # Images directory
issues/             # Weekly issue content (170+ Markdown files)
mkdocs.yml          # MkDocs configuration file
overrides/          # Custom theme templates
requirements.txt    # Python dependencies
```

#### Build Output Sample
```bash
$ mkdocs build --clean
WARNING -  Config value 'plugins': Plugin 'rss' option 'as_creation': Unrecognised configuration name: as_creation
WARNING -  Config value 'plugins': Plugin 'rss' option 'as_update': Unrecognised configuration name: as_update
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: /home/runner/work/weekly/weekly/site
WARNING -  Doc file 'issue-41.md' contains a link 'www.pexels.com', but the target is not found among documentation files.
INFO    -  Doc file 'issue-61.md' contains an unrecognized relative link
INFO    -  Documentation built in 4.46 seconds
```

#### Development Server Output Sample
```bash
$ mkdocs serve --dev-addr=0.0.0.0:8000
INFO    -  Building documentation...
INFO    -  Documentation built in 4.41 seconds
INFO    -  [01:46:00] Watching paths for changes: 'issues', 'mkdocs.yml'
INFO    -  [01:46:00] Serving on http://0.0.0.0:8000/weekly/
```

### Troubleshooting
- If build fails: Check Python version (requires 3.12+) and reinstall dependencies
- If server doesn't start: Check port 8000 is available
- If content doesn't update: Stop and restart development server
- If RSS warnings concern you: These are expected and do not affect functionality
- If external link warnings appear: These are expected for issues 41 and 61

### Making Changes
- Content changes: Edit files in `issues/` directory
- Site configuration: Edit `mkdocs.yml`
- Theme customization: Edit files in `overrides/` directory
- Always test changes with development server before committing
- Build artifacts are automatically excluded from Git commits