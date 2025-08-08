# 5ive Trackr Webpage - Live Build

## Project Structure

This is the main live build folder for the 5ive Trackr webpage and user management system, organized for clean development and deployment.

### Directory Structure

**Development Structure** (`build-development/webpage/`):
```
webpage/
├── index.html             # Admin portal landing page (root)
├── CNAME                  # Domain configuration (admin.5ivetrackr.com)
├── .gitignore             # Git ignore rules
├── README.md              # This documentation file
├── pages/                 # Additional HTML pages
│   ├── user-management.html # User management dashboard
│   └── referee-registration.html # Referee signup page
├── src/                   # Source code and assets
│   └── assets/            # Static assets
│       └── img/           # Images and graphics
└── docs/                  # Documentation
    ├── README.md          # Project documentation
    └── DEPLOYMENT-GUIDE.md # Deployment instructions
```

**Deployment Structure** (`live-build/webpage/` after sync):
```
live-build/webpage/ (identical to development structure)
├── index.html             # Admin portal landing page (root)
├── CNAME                  # Domain configuration
├── .gitignore             # Git ignore rules
├── pages/                 # Additional HTML pages
│   ├── user-management.html
│   └── referee-registration.html
├── src/                   # Assets
└── docs/                  # Documentation
```

### Page Organization

#### **Root Level**
- **index.html**: Admin portal landing page (in root directory)
  - Entry point for 5ive Trackr admin access
  - Clean interface with button to user management
  - Professional branding and styling

#### **Pages Directory** (`pages/`)
- **user-management.html**: Administrative dashboard
  - User account management
  - Live API integration
  - Admin controls and settings

- **referee-registration.html**: Referee registration system
  - Referee signup form
  - Contact information
  - Registration process

#### **Deployment Ready**
The structure is already optimized for GitHub Pages with `index.html` in the root directory.

### Key Features

- **Domain**: `admin.5ivetrackr.com`
- **Purpose**: Administrative portal for 5ive Trackr
- **Architecture**: Static HTML with live API integration
- **Deployment**: GitHub Pages with custom domain and automated file restructuring
- **Development Workflow**: Organized in `pages/` folder, deployed to repository root

### Live URLs

- **Admin Portal**: `https://admin.5ivetrackr.com/` (index.html - root)
- **User Management**: `https://admin.5ivetrackr.com/pages/user-management.html`
- **Referee Registration**: `https://admin.5ivetrackr.com/pages/referee-registration.html`

### Development

This webpage serves as the administrative portal for 5ive Trackr:
1. **Admin Portal Landing**: Clean entry point with navigation to management tools
2. **User Management Dashboard**: Administrative functions and user controls
3. **Referee Registration**: Public registration system for referees

**Development Process:**
- Work in `build-development/webpage/` with `index.html` in root and other pages in `pages/` folder
- Sync to `live-build/webpage/` for staging (maintains same structure)
- Deploy from `live-build/webpage/` to GitHub Pages (structure ready for deployment)

### Integration

- **Webapp Communication**: Links to `https://www.webapp.5ivetrackr.com/`
- **API Integration**: Uses live hosted database (five-trackr-yq6ly.ondigitalocean.app/api)
- **Cross-Platform**: Coordinates with mobile apps through webapp
- **GitHub Pages Structure**: Structure is already optimized with `index.html` in root for direct URL access

This structure is ready for GitHub Pages deployment with `index.html` in the root directory ensuring `admin.5ivetrackr.com/` loads the admin portal directly.
