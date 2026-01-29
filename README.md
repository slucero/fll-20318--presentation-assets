# Team Flame #20318 - Judging Presentation Resources

A simple GitHub Pages site providing judges with easy access to Team Flame's FLL presentation assets during remote judging sessions.

## Structure

```
├── index.html          # Main presentation page
├── styles.css          # Site styling
└── assets/
    ├── innovation/     # Innovation Project assets
    └── robot/          # Robot Presentation assets
```

## Usage

### Adding Assets

1. **Photos**: Place image files in the appropriate `assets/` subfolder, then add a `<details>` block in `index.html`
2. **Videos**: Add YouTube embed URLs to `index.html` (replace `VIDEO_ID_HERE` with actual video IDs)
3. **PDFs**: Place PDF files in `assets/` subfolder and add a link in `index.html`

### Deployment

1. Push to GitHub
2. Go to Settings > Pages
3. Set Source to "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder

## Team

**Team Flame** - FLL Team #20318
