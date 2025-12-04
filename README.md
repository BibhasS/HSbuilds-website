# HSbuilds Website

![HSbuilds Logo](https://raw.githubusercontent.com/BibhasS/HSbuilds-website/main/images/hsbulds.png)

A static multi-page website for HSbuilds built with HTML, CSS, and JavaScript, deployed via Netlify.

---

## 📋 Tech Stack

- **HTML5** - Markup structure
- **CSS3** - Styling and layout
- **JavaScript** - Interactive functionality
- **Netlify** - Hosting and continuous deployment
- **Sanitize.css** - CSS normalization for browser consistency

---

## 📁 Project Structure

HSbuilds/
├── index.html              # Homepage
├── style.css               # Global styles
├── sanitize.css            # CSS normalization
├── main.js                 # Main JavaScript logic
├── netlify.toml            # Netlify deployment configuration
├── images/                 # Image assets
│
├── 404.html                # Custom 404 error page
├── workshops.html          # Workshops page
├── workshop.css            # Workshops-specific styles
│
├── allen.html              # Allen page
├── heritage.html           # Heritage page
├── centennial.html         # Centennial page
├── chapters.html           # Chapters page
│
├── videoexample.html       # Video example page
├── videoexample.mp4        # Example video file
│
└── README.md               # This file

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- (Optional) VS Code with Live Server extension

### Running Locally

**Option 1: Direct Browser Opening**
Simply open `index.html` in your preferred browser.

**Option 2: Live Server (Recommended for Development)**
1. Open the project in VS Code
2. Install the "Live Server" extension if not already installed
3. Right-click on `index.html`
4. Select "Open with Live Server"
5. The site will open at `http://localhost:5500` (or similar) with live reload

---


## 🛠️ Development Guide

### Editing Content
- **Page Content**: Edit the respective `.html` files
- **Global Styles**: Modify `style.css`
- **Page-specific Styles**: Update `workshop.css` for workshops page
- **JavaScript**: Edit `main.js` for site-wide functionality

### Adding/Updating Assets
1. Place images in the `images/` directory
2. Update HTML references to use correct paths (e.g., `images/filename.jpg`)

### Adding New Pages
1. Create a new `.html` file
2. Link to it from existing navigation
3. Add page-specific styles if needed

---

## 📄 License

Maintained by HSbuilds contributors. All rights reserved unless otherwise specified.

---

## 🐛 Troubleshooting

### Common Issues
1. **Images not loading**: Check file paths in the `images/` directory
2. **Styles not applying**: Clear browser cache or use hard refresh (`Ctrl+F5` / `Cmd+Shift+R`)
3. **Live Server not working**: Ensure the extension is installed and activated

### Netlify Deployment Issues
- Check the Netlify deployment logs for error messages
- Verify `netlify.toml` configuration
- Ensure all file paths are correct (case-sensitive)

---

**Note**: This is a static website - no backend or database is required for operation.
