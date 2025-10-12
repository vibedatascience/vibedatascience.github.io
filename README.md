# Vibe Data Science Portfolio

Beautiful portfolio site showcasing football analytics projects and datasets.

## Features

- Modern, responsive design
- Showcases 5 major projects:
  - Podcast Analysis Viewer (with live demo)
  - Understat Players Dataset
  - Understat Teams Dataset
  - Football-Data.co.uk Big 5 Leagues Dataset
  - StatsBombPy Python Package

## Deployment to GitHub Pages

To deploy this site to your vibedatascience.github.io repository:

1. **Initialize git repository** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio site"
   ```

2. **Add remote and push**:
   ```bash
   git remote add origin https://github.com/vibedatascience/vibedatascience.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Your site will be live at https://vibedatascience.github.io

## Local Preview

To preview locally, simply open `index.html` in your browser, or use a local server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000

## Customization

- Edit `index.html` to update project descriptions or add new projects
- Modify `styles.css` to change colors, fonts, or layout
- The site uses Google Fonts (Inter) - update the font in the HTML head if desired

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Google Fonts (Inter)
- SVG icons
- Responsive design for mobile, tablet, and desktop

---

Created with data from vibedatascience GitHub repositories.
