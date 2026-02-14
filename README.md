# Pinnu Valentine's Day + Portfolio

## Files
- `index.html` - Valentine's Day challenge (landing page)
- `portfolio.html` - Pinnu Sekhon portfolio site

## Deploy to Vercel (Easiest - Free)

### Option A: Drag & Drop
1. Go to https://vercel.com and sign up (free)
2. Click "Add New Project"
3. Choose "Upload" and drag the `deploy` folder
4. It deploys instantly and gives you a URL like `your-project.vercel.app`
5. Add your custom domain if you have one (pinnusekhon.com)

### Option B: Via CLI
```bash
npm i -g vercel
cd deploy
vercel
```
Follow prompts. Done in 30 seconds.

## Deploy to Netlify (Also Free)

1. Go to https://netlify.com and sign up
2. Drag the `deploy` folder onto the deploy area
3. Get your URL instantly
4. Add custom domain in settings

## Deploy to GitHub Pages (Free)

1. Create a new repo on GitHub
2. Upload both HTML files
3. Go to Settings > Pages > Source: main branch
4. Your site is live at `yourusername.github.io/reponame`

## Custom Domain Setup
If you own pinnusekhon.com:
1. In Vercel/Netlify, go to project settings > Domains
2. Add `pinnusekhon.com`
3. Update your domain's DNS:
   - For Vercel: Add CNAME record pointing to `cname.vercel-dns.com`
   - For Netlify: Add CNAME record pointing to `your-site.netlify.app`

## How It Works
- Visitor lands on `index.html` (Valentine's challenge)
- After completing all challenges + love letter + gift unwrap
- "See Your Website" button links to `portfolio.html`
- Both pages are self-contained single HTML files, no build step needed

## Notes
- Portfolio images are embedded as base64 (no external files needed)
- Map uses Leaflet CDN (needs internet connection)
- Fonts load from Google Fonts CDN
- Everything else is self-contained
