# AI Tools Directory 🤖

> The ultimate curated collection of AI tools and resources.

[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Support](#support)

## Overview
AI Tools is a responsive directory website showcasing artificial intelligence tools in a clean, three-column grid layout. The site is built with HTML, CSS, and JavaScript, making it easy to customize and maintain.

## Features
- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 📱 Mobile-friendly design
- 🚀 Fast loading times
- 🎨 Customizable styling

## Getting Started

### Prerequisites
- Git
- Text editor (VS Code recommended)
- Basic knowledge of HTML/CSS

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-tools-directory.git
```

2. Navigate to project directory:
```bash
cd ai-tools-directory
```

3. Open `index.html` in your browser to view the site locally.

## Directory Structure
```
ai-tools-directory/
├── index.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   ├── main.js
│   └── search.js
├── images/
│   └── tools/
└── data/
    └── directory.json
```

## Customization

### Adding Directory Items
1. Open `data/directory.json`
2. Add new items in the following format:
```json
{
  "name": "Tool Name",
  "description": "Tool description",
  "category": "Category",
  "url": "https://toolurl.com",
  "image": "images/tools/tool-image.png"
}
```

### Modifying Categories
1. Open `index.html`
2. Locate the category section:
```html
<div class="categories">
  <!-- Add or modify categories here -->
  <button class="category-btn" data-category="all">All</button>
  <button class="category-btn" data-category="chatbots">Chatbots</button>
</div>
```

### Updating Hero Section
1. Open `index.html`
2. Modify the hero section content:
```html
<div class="hero">
  <h1>Your New Title</h1>
  <p>Your new description</p>
</div>
```

### Customizing Colors
1. Open `css/style.css`
2. Modify the root variables:
```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

## Deployment

### Netlify Deployment
1. Create a Netlify account
2. Connect your GitHub repository
3. Configure build settings:
   - Build command: `none`
   - Publish directory: `/`
4. Click "Deploy"

## Custom Domain Setup

### Using Custom Domain with Netlify
1. Go to Netlify site settings
2. Navigate to "Domain Management"
3. Click "Add Custom Domain"
4. Follow DNS configuration instructions
5. Wait for SSL certificate provisioning

### Using Custom Domain with GitHub Pages
1. Add CNAME file to repository
2. Configure DNS settings
3. Enable HTTPS in repository settings

## Troubleshooting

### Common Issues
- **Images not loading**: Check file paths in `directory.json`
- **Search not working**: Verify `search.js` is properly linked
- **Categories not filtering**: Check category names match in HTML and JSON

### Browser Console Errors
1. Open browser developer tools (F12)
2. Check console for error messages
3. Verify all JavaScript files are loading

## Support
- 📧 Email: support@aitools.com
- 💬 Discord: [Join our community](https://discord.gg/aitools)
- 📖 Documentation: [Full documentation](https://docs.aitools.com)

## Contributing
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create pull request

## License
MIT License - see [LICENSE.md](LICENSE.md)

---

Made with ❤️ by [Your Name]