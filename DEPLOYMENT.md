# Deployment Guide

## Quick Deploy Options

### Option 1: Vercel (Recommended - Easiest)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel auto-detects Nuxt 3 and configures everything
6. Click "Deploy"
7. Your site will be live in ~2 minutes!

**Vercel automatically:**
- Detects Nuxt 3
- Runs `npm run build`
- Serves from `.output/public`
- Gives you a free `.vercel.app` domain

### Option 2: Netlify

1. Push code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "Add new site" > "Import an existing project"
4. Connect your GitHub repo
5. Build settings:
   - Build command: `npm run build`
   - Publish directory: `.output/public`
6. Click "Deploy site"

### Option 3: Firebase Hosting

```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login
firebase login

# Initialize
firebase init hosting

# Build
npm run build

# Deploy
firebase deploy --only hosting
```

### Option 4: GitHub Pages (Static)

```bash
# Generate static site
npm run generate

# The dist folder contains your static site
# Push to gh-pages branch or configure GitHub Pages
```

## Environment Setup

If you add environment variables later:

1. Create `.env` file (already in .gitignore)
2. Add variables:
```
NUXT_PUBLIC_API_URL=https://api.example.com
```
3. In Vercel/Netlify, add the same variables in their dashboard

## Post-Deployment Checklist

- [ ] Test on mobile device
- [ ] Verify all links work
- [ ] Test mobile menu toggle
- [ ] Check page load speed
- [ ] Run Lighthouse audit
- [ ] Take Pixelay screenshots for comparison
- [ ] Update README with live URL

## Pixelay Screenshots After Deployment

Once deployed:

1. Install Pixelay Chrome extension
2. Navigate to your live site
3. Load the Figma design
4. Take overlay screenshots:
   - Desktop view (1920x1080 or 1440x900)
   - Mobile view (375x667 or 414x896)
5. Save as:
   - `pixelay/pixelay-desktop.png`
   - `pixelay/pixelay-mobile.png`
6. Document differences in `pixelay/notes.md`
