# 5ive Trackr Admin Portal

A secure user management interface for creating referee and league manager accounts.

## Quick Deploy to GitHub Pages (Private Repository)

1. **Clone the repository**: `https://github.com/FiveTrackr/five-trackr-site`
2. **Enable GitHub Pages** in repository settings (Private repo supported with GitHub Pro)
3. **Set custom domain**: `admin.5ivetrackr.com`

## Repository Details

- **Owner**: FiveTrackr
- **Repo**: five-trackr-site
- **Visibility**: Private (GitHub Pro)
- **Pages URL**: `https://fivetrackr.github.io/five-trackr-site/`
- **Custom Domain**: `https://admin.5ivetrackr.com`

## Features

- 🔐 Password protected access
- 👥 Create referee and league manager accounts
- 🔗 Direct API integration with main app
- 📱 Mobile responsive design
- ✨ Professional UI matching 5ive Trackr branding

## Security

- Admin password: `Ziggydog123!`
- HTTPS enforced
- API validation

## API Endpoints

Connects to: `https://five-trackr-yq6ly.ondigitalocean.app/api`

- `POST /auth/register` - Create new user
- `GET /admin/users` - List users (optional)
- `DELETE /admin/users/:email` - Delete user (optional)

## Domain Setup

### Squarespace DNS Configuration
Add CNAME record:
- **Name**: `admin`
- **Value**: `fivetrackr.github.io`

This creates: `https://admin.5ivetrackr.com`

## Local Development

Simply open `index.html` in a web browser. No build process required.

## Support

For issues, contact your development team or check the main 5ive Trackr documentation.
