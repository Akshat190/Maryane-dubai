# Maryanne Advisors Business Setup Website

This is a static website for Maryanne Advisors, a business setup consultancy in Dubai, UAE. The site helps with UAE business setup services including company formation, business licensing, visa processing, and banking assistance.

## Project Structure

- `index.html` - Main entry point for the website (moved from `/ma/page/index.html` and updated for Netlify deployment)
- Various asset directories containing CSS, JavaScript, images, and other resources
- Image files copied to root directory for proper loading: `freezone.jpg`, `mainland.jpg`, `bk.jpg`, `banner.webp`, `logo.png`
- `_redirects` - Netlify redirect configuration
- `netlify.toml` - Netlify deployment configuration

## Deployment to Netlify

### Method 1: Direct Drag and Drop
1. Go to [Netlify](https://app.netlify.com/)
2. Create a new account or sign in
3. Drag and drop the entire project folder onto the Netlify dashboard
4. Netlify will automatically deploy the site

### Method 2: Git Integration
1. Push this project to a GitHub, GitLab, or Bitbucket repository
2. Connect your repository to Netlify
3. Netlify will automatically deploy on pushes to the main branch

### Method 3: Netlify CLI
1. Install the Netlify CLI: `npm install -g netlify-cli`
2. Run `netlify deploy` from the project directory
3. Choose "Deploy to production" to publish your site

## Configuration

The site is configured to work properly on Netlify with:
- Preload links updated to reference images from the root directory
- All necessary images copied to the root directory
- Proper redirect configuration in `_redirects`
- Build configuration in `netlify.toml`

## Features

- Fully responsive design optimized for all devices
- Business setup services for UAE market
- Contact forms with validation
- Image optimization and lazy loading
- Performance optimized for fast loading

## Notes

- The original site was located at `/ma/page/index.html`
- All image paths have been updated to work from the root directory
- External assets (icons, CDN-hosted images) continue to load from their original sources
- The site is ready for immediate deployment on Netlify