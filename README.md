# GitHub Pages Template

A modern, responsive website template for GitHub Pages with automatic deployment using GitHub Actions.

## Features

- Clean, modern design
- Fully responsive layout
- Automatic deployment to GitHub Pages
- Easy to customize
- Built with HTML and CSS
- No JavaScript required

## Getting Started

1. Clone this repository
2. Customize the content in `index.html`
3. Modify the styles in `styles.css` to match your preferences
4. Push your changes to the main branch
5. GitHub Actions will automatically deploy your site

## Customization

### Changing Colors

The color scheme can be easily modified by editing the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --text-color: #1f2937;
    --background-color: #ffffff;
    --secondary-background: #f3f4f6;
}
```

### Adding Content

Edit the sections in `index.html` to add your own content. The template includes:

- Navigation menu
- Hero section
- About section
- Contact section
- Footer

## Deployment

The site is automatically deployed to GitHub Pages when you push to the main branch. The deployment is handled by the GitHub Actions workflow in `.github/workflows/deploy.yml`.

## License

This template is open source and available under the MIT License.