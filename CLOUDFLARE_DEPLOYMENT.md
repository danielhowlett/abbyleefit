# Cloudflare Pages Deployment Configuration

## Build Settings
- **Framework**: None (Static HTML)
- **Build Command**: Not required (leave empty)
- **Build Output Directory**: `/` (root directory)
- **Root Directory**: `/` (deploy entire project root)

## Important Files
- `index.html` - Main website entry point
- `_redirects` - URL rewriting rules for SPA routing and proper 404 handling

## Deployment Steps

### Option 1: Deploy via Git (Recommended)
1. Connect your GitHub repository to Cloudflare Pages
2. Set the following build settings:
   - **Build command**: (leave empty)
   - **Build output directory**: (leave empty)
3. Click "Save and Deploy"
4. Your site will be deployed to `https://your-project.pages.dev`

### Option 2: Deploy via Cloudflare Dashboard
1. Go to Cloudflare Pages
2. Click "Create a project" > "Direct upload"
3. Upload all files from this repository
4. Click "Deploy site"

## Important Notes
- No npm build step is required
- Cloudflare Pages will serve `index.html` as the entry point
- The `_redirects` file ensures all routes return `index.html` (200 status, not 302 redirect)
- This prevents 404 errors on direct page refreshes and enables proper SPA navigation

## Custom Domain Setup
After deployment:
1. In Cloudflare Pages, go to your project settings
2. Add your custom domain (e.g., abbyleefit.com)
3. Update DNS records as instructed by Cloudflare
4. SSL/TLS certificate is automatically provisioned

## Environment Variables
No environment variables are required for this project.

## External Dependencies
The site loads the following from CDNs (ensure Cloudflare Pages isn't blocking these):
- Tailwind CSS: https://cdn.tailwindcss.com
- Google Fonts: fonts.googleapis.com
- Google Material Symbols: fonts.googleapis.com
- Hero & About images: Google URLs (external)

## Troubleshooting
- If routes return 404: Verify `_redirects` file exists in the build output
- If styles don't load: Check Cloudflare firewall rules aren't blocking CDN access
- If images don't show: External image URLs may need CORS configuration
