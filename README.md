# Simple Portfolio Website

A clean, responsive, and minimal portfolio website built with HTML, CSS, and Vanilla JavaScript.

## Features
- **Responsive Design**: Works on mobile, tablet, and desktop.
- **Single Page Layout**: Smooth scrolling navigation.
- **Resume Viewer**: Dedicated page to view and download your CV.
- **No Dependencies**: Pure HTML/CSS/JS.

## Project Structure
```
/portfolio_site
├── index.html       # Main portfolio page
├── resume.html      # PDF viewer page
├── css
│   └── style.css    # Global styles
├── js
│   └── script.js    # Interactivity
└── assets
    └── resume.pdf   # Your PDF resume
```

## How to Use
1. **Replace the Resume**: 
   - Go to the `assets` folder.
   - Replace `resume.pdf` with your actual PDF resume file.
   - Ensure the filename remains `resume.pdf`.

2. **Customize Content**:
   - Open `index.html` and update your Name, Text, Skills, and Projects.
   - Update Social Links in the footer.

## Running Locally
To view the site locally, you can simply open `index.html` in your browser. 
However, for the best experience (and to avoid CORS issues with some local file loading), it's recommended to use a local server.

### Using Python (if installed)
```bash
python3 -m http.server
```
Then visit `http://localhost:8000`.

### Using VS Code Live Server
Right-click `index.html` and select "Open with Live Server".

## Deployment

### GitHub Pages
1. Push this code to a GitHub repository.
2. Go to Settings > Pages.
3. Select `main` branch and `/root` folder.
4. Save.

### Netlify
1. Drag and drop the `portfolio_site` folder onto the Netlify dashboard.
2. Or connect your GitHub repository for continuous deployment.
