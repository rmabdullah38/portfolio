# Deployment Guide for ronnyabdullah.com

## GitHub Setup
1. Create a new repository on GitHub (e.g., "portfolio" or "ronnyabdullah-website")
2. Connect your local repository:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

## Domain Deployment Options

### Option 1: GitHub Pages (Free)
1. Go to your GitHub repository settings
2. Scroll down to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`
6. To use your custom domain:
   - Add your domain in the "Custom domain" field
   - Create a CNAME file in your repository root with content: `ronnyabdullah.com`
   - Update your Namecheap DNS settings (see below)

### Option 2: Netlify (Free tier available)
1. Go to netlify.com and sign up
2. Connect your GitHub repository
3. Deploy settings: Build command: (leave empty), Publish directory: `/`
4. Your site will be available at a Netlify subdomain
5. To use custom domain:
   - Go to Domain settings
   - Add custom domain: `ronnyabdullah.com`
   - Update DNS settings (see below)

### Option 3: Vercel (Free tier available)
1. Go to vercel.com and sign up
2. Import your GitHub repository
3. Deploy settings: Framework preset: Other, Root directory: `/`
4. Your site will be available at a Vercel subdomain
5. To use custom domain:
   - Go to Domains section
   - Add domain: `ronnyabdullah.com`
   - Update DNS settings (see below)

## Namecheap DNS Configuration

For any hosting provider, you'll need to update your Namecheap DNS settings:

1. Log into your Namecheap account
2. Go to "Domain List" → "Manage" for ronnyabdullah.com
3. Go to "Advanced DNS" tab
4. Add these records:

### For GitHub Pages:
- Type: CNAME
- Host: @
- Value: YOUR_USERNAME.github.io
- TTL: Automatic

### For Netlify:
- Type: CNAME
- Host: @
- Value: YOUR_SITE_NAME.netlify.app
- TTL: Automatic

### For Vercel:
- Type: CNAME
- Host: @
- Value: YOUR_SITE_NAME.vercel.app
- TTL: Automatic

## Recommended: GitHub Pages + Custom Domain

This is the simplest and most cost-effective option:
1. Use GitHub Pages for hosting (free)
2. Connect your custom domain
3. Enable HTTPS (automatic with GitHub Pages)

## Testing Your Deployment
After deployment, test:
- All pages load correctly
- Navigation works
- Contact form submits properly
- Mobile responsiveness
- All links and images work 