# 5ive Trackr Webpage - Live Build

## Project Structure

This is the main live build folder for the 5ive Trackr webpage and user management system, organized for clean development and deployment.

### Directory Structure

```
webpage/
├── pages/                 # All HTML pages (simplified structure)
│   ├── index.html         # Admin portal landing page
│   ├── user-management.html # User management dashboard
│   └── referee-registration.html # Referee signup page
│
├── src/                   # Source code and assets
│   └── assets/            # Static assets
│       └── img/           # Images and graphics
│
├── docs/                  # Documentation
│   ├── README.md          # Project documentation
│   └── DEPLOYMENT-GUIDE.md # Deployment instructions
│
├── .gitignore             # Git ignore rules
└── CNAME                  # Domain configuration (admin.5ivetrackr.com)
```

### Page Organization

#### **All Pages** (`pages/`)
- **index.html**: Admin portal landing page
  - Entry point for 5ive Trackr admin access
  - Clean interface with button to user management
  - Professional branding and styling

- **user-management.html**: Administrative dashboard
  - User account management
  - Live API integration
  - Admin controls and settings

- **referee-registration.html**: Referee registration system
  - Referee signup form
  - Contact information
  - Registration process

### Key Features

- **Domain**: `admin.5ivetrackr.com`
- **Purpose**: Public website + User management
- **Architecture**: Static HTML with live API integration
- **Deployment**: GitHub Pages with custom domain

### Live URLs

- **Admin Portal**: `https://admin.5ivetrackr.com/` (index.html)
- **User Management**: `https://admin.5ivetrackr.com/user-management.html`
- **Referee Registration**: `https://admin.5ivetrackr.com/referee-registration.html`

### Development

This webpage serves as the administrative portal for 5ive Trackr:
1. **Admin Portal Landing**: Clean entry point with navigation to management tools
2. **User Management Dashboard**: Administrative functions and user controls
3. **Referee Registration**: Public registration system for referees

### Integration

- **Webapp Communication**: Links to `https://www.webapp.5ivetrackr.com/`
- **API Integration**: Uses live hosted database (five-trackr-yq6ly.ondigitalocean.app/api)
- **Cross-Platform**: Coordinates with mobile apps through webapp
- **Simplified Structure**: All pages in single `pages/` directory for easy navigation

This clean structure provides a streamlined admin portal while maintaining easy navigation and deployment.
