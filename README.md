# Nikhil Kumar - Academic Website

Personal academic website built with Jekyll and hosted on GitHub Pages.

## Local Development

To run locally (requires Ruby):

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`

## Deployment

This site is configured for GitHub Pages. Push to the `main` branch and GitHub will automatically build and deploy.

## Structure

- `_config.yml` - Site configuration
- `_layouts/` - Page templates
- `_includes/` - Reusable components (header, footer)
- `assets/css/` - Stylesheets
- `index.md` - Home page
- `research.md` - Research page
- `teaching.md` - Teaching page

## Customization

- **Add a photo**: Replace the placeholder in `index.md` with `<img src="/assets/img/photo.jpg" alt="Nikhil Kumar">` and add your photo to `assets/img/`
- **Update content**: Edit the markdown files directly
- **Change colors**: Modify CSS variables in `assets/css/style.css`
