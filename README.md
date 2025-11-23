# Cardiovascular Disease Risk Assessment (QRISK) Website

A modern, interactive patient education website about cardiovascular disease risk assessment and statin therapy.

## Features

- 🎨 **Modern, responsive design** - Works on all devices
- 🔄 **Interactive risk calculator** - Compare statin benefits at different risk levels
- 📱 **Mobile-friendly** - Fully responsive layout
- 🎯 **Accordion sections** - Collapsible side effect information
- 💙 **Patient-friendly** - Clear, accessible language

## Quick Start

### Deploy to GitHub Pages

1. **Create a new repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it something like `qrisk-info` or `cvd-risk-assessment`
   - Make it public

2. **Upload the file**
   - Upload `index.html` to your repository
   - You can drag and drop directly on GitHub or use Git

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Click on "Pages" in the left sidebar
   - Under "Source", select the `main` branch
   - Click "Save"

4. **Access your site**
   - Your site will be live at: `https://[your-username].github.io/[repository-name]/`
   - It may take a few minutes to deploy

## Customization

### Update Contact Information

Find and replace "Beacon Medical Group" with your practice name in the HTML.

### Modify Colors

Edit the CSS variables at the top of the `<style>` section:

```css
:root {
    --primary-color: #2563eb;  /* Main blue color */
    --secondary-color: #dc2626; /* Red for warnings */
    --accent-color: #059669;    /* Green for success */
}
```

### Add Your Logo

Add this code in the hero section:

```html
<img src="your-logo.png" alt="Practice Logo" style="max-width: 200px; margin-bottom: 1rem;">
```

### Update Links

Update the smoking cessation and weight management links to your local services.

## Technical Details

- Pure HTML/CSS/JavaScript - no dependencies
- Lightweight and fast loading
- Accessible and SEO-friendly
- Works offline after first visit

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

Feel free to adapt this for your practice. Please ensure all medical information is reviewed by appropriate clinical staff before deployment.

## Credits

Based on patient information developed by Beacon Medical Group.
