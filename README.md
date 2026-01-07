# Sahil Mahbub - Personal Website

A minimalistic personal portfolio website showcasing my professional experience, skills, and education.

## Features

- ✨ Clean, minimalistic design
- 🎨 Brand colors based on personal logo (black, white, green)
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🚀 Fast loading and optimized
- 📄 Downloadable resume

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)

## Setup Instructions

### Option 1: GitHub Pages (Recommended)

1. Create a new repository named `sahil3429.github.io`
2. Upload all files to the repository: 
   - `index.html`
   - `styles.css`
   - `script.js`
   - `logo.png` (your logo image)
   - `sahil_mahbub_resume.pdf` (your resume PDF)
3. Go to repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be live at `https://sahil3429.github.io`

### Option 2: Custom Domain

If you want to use a custom domain: 

1. Follow the steps above for GitHub Pages
2. Add a `CNAME` file with your domain name
3. Configure your domain's DNS settings to point to GitHub Pages

## Customization

### Update Contact Information

In `index.html`, update the contact section (around line 167):

```html
<a href="mailto:your.email@example.com" class="contact-btn">
<a href="https://linkedin.com/in/yourprofile" target="_blank" class="contact-btn">
```

### Add Your Logo

Replace the placeholder logo by adding your logo image file as `logo.png` in the root directory.

### Add Your Resume

Add your resume PDF as `sahil_mahbub_resume.pdf` in the root directory.

### Color Scheme

To change colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-green: #00FF00;
    --dark-green: #00CC00;
    --black:  #000000;
    --white: #FFFFFF;
}
```

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── logo.png           # Your logo image
├── sahil_mahbub_resume. pdf  # Your resume
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2026 Sahil Mahbub. All rights reserved. 