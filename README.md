# HSbuilds Website

![HSbuilds Logo](https://raw.githubusercontent.com/BibhasS/HSbuilds-website/main/images/hsbulds.png)

This repository contains the **source code for the HSbuilds website**.  
It is a static multi-page website built using HTML, CSS, and JavaScript and deployed through Netlify.

---

## Tech Stack

- HTML5  
- CSS3  
- JavaScript  
- Netlify (Hosting & Deployment)  
- Sanitize.css (Browser consistency)  

---

## Project Structure

\`\`\`
HSbuilds/
│
├── index.html           # Homepage
├── style.css            # Global styles
├── sanitize.css         # CSS normalization
├── main.js              # Frontend logic
├── netlify.toml         # Netlify config
├── images/              # Assets
│
├── 404.html             # Custom 404 page
├── workshops.html       # Workshop page
├── workshop.css         # Workshop styles
│
├── allen.html
├── heritage.html
├── centennial.html
├── chapters.html
│
├── videoexample.html
├── videoexample.mp4
│
└── README.md
\`\`\`

---

## How to Run Locally

### Option 1: Open in Browser
Open `index.html` directly in your browser.

### Option 2: Using Live Server (Recommended)
1. Open the project folder in VS Code  
2. Install the **Live Server** extension  
3. Right-click `index.html`  
4. Click **Open with Live Server**  

---

## Deployment

This site is deployed using **Netlify**.

To redeploy:
1. Push changes to the `main` branch  
2. Netlify will automatically rebuild the site  

Deployment settings are managed in:

\`\`\`
netlify.toml
\`\`\`

---

## Editing Guide

### Modify Content
Update HTML files directly (e.g., `index.html`, `workshops.html`, etc.).

### Modify Styling
- `style.css` → global styles  
- `workshop.css` → workshop page styles  

### Update Images
Add or replace assets in:

\`\`\`
images/
\`\`\`

Then update the image paths inside the HTML.

### JavaScript Logic
Edit:

\`\`\`
main.js
\`\`\`

---

## Contributors

- Bibhas Sharma  
- Sreekar Jarajapu  
- Narein Vignesh  
- Abhi Reddy  
- Anvi Siddabhattuni  
- Christian Fowler  

---

## License

Maintained by HSbuilds contributors.  
All rights reserved unless otherwise specified.
