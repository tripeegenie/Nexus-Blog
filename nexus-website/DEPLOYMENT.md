# NEXUS - Netlify Deployment Guide

## Quick Deploy to Netlify

### Method 1: Drag & Drop (Easiest)

1. Go to [Netlify](https://www.netlify.com/)
2. Sign up or log in
3. Drag the entire `nexus-website` folder onto Netlify's deploy zone
4. Your site will be live in seconds!

### Method 2: Git Repository (Recommended)

1. Create a new repository on GitHub
2. Upload all files from the `nexus-website` folder
3. Go to [Netlify](https://www.netlify.com/)
4. Click "Add new site" → "Import an existing project"
5. Connect your GitHub account
6. Select your repository
7. Netlify will auto-detect settings and deploy

### Method 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy from the nexus-website directory
cd nexus-website
netlify deploy --prod
```

## Custom Domain Setup

1. Go to your site settings in Netlify
2. Click "Domain management"
3. Click "Add custom domain"
4. Follow the instructions to configure your DNS

## Site Settings

- **Build command:** (none needed - static HTML)
- **Publish directory:** `.` (root)
- **Functions directory:** (not used)

## Performance Optimizations

Your site is already optimized with:
- ✅ Minified animations
- ✅ Optimized images and fonts
- ✅ Mobile-responsive design
- ✅ Fast loading times

## Post-Deployment

After deployment, your site will be available at:
- **Netlify subdomain:** `your-site-name.netlify.app`
- **Custom domain:** (if configured)

## Support

For issues or questions, contact: Prajwal Yamgar

---

© 2026 NEXUS INDUSTRIES
