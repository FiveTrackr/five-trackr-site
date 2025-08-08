# 5ive Trackr Admin Portal - Deployment Guide

## GitHub Pages + Custom Domain Setup (Private Repository)

### Step 1: Create GitHub Repository
1. Go to GitHub.com and create a new repository
2. Name it: `five-trackr-site`
3. **Make it PRIVATE** (GitHub Pro allows private repos for Pages)
4. Initialize with README

### Step 2: Upload Files
```bash
git clone https://github.com/FiveTrackr/five-trackr-site.git
cd five-trackr-site
# Copy user-management.html as index.html
cp "../path/to/user-management.html" index.html
git add .
git commit -m "Add admin portal"
git push origin main
```

### Step 3: Enable GitHub Pages
1. Repository Settings → Pages
2. Source: "Deploy from a branch"
3. Branch: main / (root)
4. **Visibility**: Private (GitHub Pro feature)
5. Save

### Step 4: Custom Domain Setup (Squarespace)
1. **In Squarespace DNS Settings**:
   - Add CNAME record:
   - Name: `admin` (creates admin.5ivetrackr.com)
   - Value: `fivetrackr.github.io`

2. **In GitHub Repository**:
   - Settings → Pages → Custom domain
   - Enter: `admin.5ivetrackr.com`
   - Check "Enforce HTTPS"

### Step 5: Verify Setup
- Wait 5-10 minutes for DNS propagation
- Visit: `https://admin.5ivetrackr.com`
- Should show your user management portal

## Alternative: Netlify Deploy (Easier)

### One-Click Deploy
1. Fork this repository
2. Connect to Netlify
3. Set custom domain in Netlify settings
4. Update Squarespace DNS to point to Netlify

## Security Notes
- The page is password protected (Ziggydog123!)
- Consider adding IP restrictions for production use
- Monitor access logs regularly

## API Configuration
The page connects to:
```
https://five-trackr-yq6ly.ondigitalocean.app/api
```

Ensure your API supports:
- POST /api/auth/register
- GET /api/admin/users (optional)
- DELETE /api/admin/users/:email (optional)
