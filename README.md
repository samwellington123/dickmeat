# dickmeat.com

A simple one-page website with header text and an image.

## Files

- `index.html` - Main website page
- `IMG_5826.jpeg` - Image displayed on the site

## Deployment

### Option 1: Porkbun Hosting (if available)

1. Log into your Porkbun account
2. Navigate to your domain settings for dickmeat.com
3. Look for hosting or file manager options
4. Upload both `index.html` and `IMG_5826.jpeg`

### Option 2: GitHub Pages (Free)

1. Create a GitHub repository
2. Push these files to the repository
3. Go to repository Settings → Pages
4. Enable GitHub Pages from the main branch
5. Point your Porkbun DNS to GitHub Pages:
   - Add a CNAME record pointing to `yourusername.github.io`
   - Add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

### Option 3: Netlify (Free)

1. Sign up at netlify.com
2. Drag and drop this folder into Netlify
3. In Porkbun DNS settings, add a CNAME record pointing to your Netlify subdomain

### Option 4: Any Web Host

Simply upload both files to your web hosting provider's public directory (often called `public_html`, `www`, or `htdocs`).

## Preview Locally

Open `index.html` in any web browser to preview the site.


