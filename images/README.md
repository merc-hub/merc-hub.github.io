# Project Images Folder

This folder is for storing images used in the portfolio website.

## Recommended Organization

```
images/
├── projects/
│   ├── portfolio-website.jpg
│   ├── contact-form.jpg
│   ├── semantic-html.jpg
│   ├── accessibility-tool.jpg
│   ├── responsive-layout.jpg
│   └── javascript-projects.jpg
├── about/
│   └── profile-photo.jpg
└── portfolio-banner.jpg
```

## Usage

### Adding Project Images
1. Place project screenshot images in `images/projects/` folder
2. Update the project cards in `projects.html`
3. Replace the emoji placeholders with actual image tags:

```html
<!-- Change from -->
<div class="project-image">🌐</div>

<!-- To -->
<img src="images/projects/portfolio-website.jpg" alt="Personal Portfolio Website">
```

### Profile Image
1. Add a profile photo to `images/about/` folder
2. Add image to about.html with proper alt text

### Image Guidelines
- **Format**: JPG or PNG
- **Size**: Optimize for web (max 1MB per image)
- **Dimensions**: 
  - Project cards: 500x300px recommended
  - Profile photo: 400x400px recommended
- **Alt Text**: Always include descriptive alt text for accessibility

## Current Status
- ✅ Folder structure created and ready
- ❌ Images not yet added (add your project screenshots)
- 📝 Update HTML to reference images when ready

## Tips
- Use free tools like TinyPNG to compress images
- Screenshots can be taken using browser dev tools
- Use consistent lighting and style for all project images
- Test images display correctly before sharing portfolio
