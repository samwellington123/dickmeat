# dickmeat.com

🌐 **Live Site:** https://samwellington123.github.io/dickmeat/  
🔗 **Custom Domain:** dickmeat.com (pending DNS configuration)

A simple one-page website with header text and an image, featuring PostHog analytics.

## Features

- 📱 Fully responsive design
- 🎨 Modern gradient background with clean UI
- 📊 PostHog analytics integration for visitor tracking
- ⚡ Hosted on GitHub Pages (free)

## Files

- `index.html` - Main website page with PostHog tracking
- `IMG_5826.jpeg` - Image displayed on the site
- `README.md` - This file
- `CNAME` - Custom domain configuration

## Current Deployment

✅ **Hosted on GitHub Pages**  
Repository: https://github.com/samwellington123/dickmeat  
Live URL: https://samwellington123.github.io/dickmeat/

## Setting Up Custom Domain (dickmeat.com)

To point your Porkbun domain to GitHub Pages, add these DNS records:

### A Records (for apex domain)
Add four A records with name `@`:
- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

### CNAME Record (for www subdomain)
- Name: `www`
- Points to: `samwellington123.github.io`

### In GitHub Repository Settings
1. Go to Settings → Pages
2. Under "Custom domain", enter: `dickmeat.com`
3. Click Save
4. Wait for DNS to propagate (up to 24 hours)
5. Enable "Enforce HTTPS" once available

## Analytics

PostHog analytics is integrated to track:
- Page views
- Session recordings
- User behavior
- Traffic sources

## Local Development

To run locally:
```bash
python3 -m http.server 3000
```

Then visit: http://localhost:3000


