# Restored Masonry - Professional Website

A beautiful, responsive website for Restored Masonry, specializing in heritage masonry restoration and building pathology for historic buildings in the Greater Ottawa Area.

## Features

- **Modern Design**: Clean, professional aesthetic with earth-tone color scheme
- **Fully Responsive**: Mobile-first design that works on all devices
- **Fast Loading**: Optimized HTML, CSS, and minimal JavaScript
- **SEO Optimized**: Proper meta tags, semantic HTML, and fast loading
- **Contact Form**: Client-side validation with user feedback
- **Smooth Animations**: Subtle scroll animations and transitions

## Pages

- **Home**: Hero section, services overview, company highlights
- **About**: Company story, expertise, and commitment to heritage preservation
- **Services**: Detailed service descriptions with images and features
- **Contact**: Contact form, company information, and service area

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript
- Google Fonts (Playfair Display, Inter)

## Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. For a local server, use Python:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Deployment

This site is designed for GitHub Pages deployment:

1. Push to GitHub repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. The site will be available at `https://yourusername.github.io/repository-name`

## Customization

### Colors
Edit the CSS custom properties in `css/style.css`:

```css
:root {
    --primary-color: #8b6f47;    /* Brown */
    --secondary-color: #d4a574;  /* Tan */
    --accent-color: #c97c5e;     /* Terracotta */
}
```

### Content
Update text content directly in the HTML files. Contact information is in the footer and contact page.

### Images
Add images to the `img/` folder and update the `src` attributes in the HTML files.

## Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Lighthouse score: 95+ (estimated)
- Fast loading with minimal assets
- Optimized images with lazy loading
- Efficient CSS and JavaScript

## License

This project is proprietary to Restored Masonry.