# Reflections EPK

Electronic Press Kit for Reflections - A musical project by Justin Bonagura Moran.

## Overview

This repository contains the official Electronic Press Kit (EPK) website for Reflections, featuring information about the project, singles, upcoming album, and contact information.

## Deployment on GitHub Pages

To deploy this site on GitHub Pages:

1. **Create a new repository** on GitHub named `reflections-epk` (or your preferred name)

2. **Initialize and push the code**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Reflections EPK"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/reflections-epk.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your site**:
   - Your site will be available at: `https://YOUR_USERNAME.github.io/reflections-epk/`
   - It may take a few minutes for the site to become available

## Features

- Clean, modern design without Canva branding
- Fully responsive layout
- Smooth animations and hover effects
- Direct links to all singles on Spotify
- Contact information and social media links
- Optimized for performance and SEO

## Customization

To customize the content:

- Edit the `index.html` file directly
- Update colors in the CSS `:root` variables section
- Replace the hero background image URL with your own
- Add or modify singles in the singles section
- Update contact links as needed

## Local Development

To test the site locally:

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   ```

## License

© 2025 Reflections. All rights reserved.