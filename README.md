# 5ive Trackr Webpage - Live Build

## Project Structure

This is the main live build folder for the 5ive Trackr webpage and user management system, organized for clean development and deployment.

### Directory Structure

```
webpage/
├── src/                    # Source code and assets
│   ├── pages/             # Public-facing pages
│   │   ├── index.html     # Main website homepage
│   │   └── referee-registration.html # Referee signup page
│   ├── admin/             # Administrative pages
│   │   └── user-management.html # User management dashboard
│   └── assets/            # Static assets
│       └── img/           # Images and graphics
│
├── build/                 # Build and deployment files
│   └── (deployment scripts and configs)
│
├── docs/                  # Documentation
│   ├── README.md          # Project documentation
│   └── DEPLOYMENT-GUIDE.md # Deployment instructions
│
├── .git/                  # Git repository
├── .gitignore             # Git ignore rules
└── CNAME                  # Domain configuration (admin.5ivetrackr.com)
```

### Page Organization

#### **Public Pages** (`src/pages/`)
- **index.html**: Main website homepage
  - Landing page for 5ive Trackr
  - Subscription information
  - Marketing content

- **referee-registration.html**: Referee registration system
  - Referee signup form
  - Contact information
  - Registration process

#### **Admin Pages** (`src/admin/`)
- **user-management.html**: Administrative dashboard
  - User account management
  - Live API integration
  - Admin controls and settings

### Key Features

- **Domain**: `admin.5ivetrackr.com`
- **Purpose**: Public website + User management
- **Architecture**: Static HTML with live API integration
- **Deployment**: GitHub Pages with custom domain

### Live URLs

- **Main Website**: `https://admin.5ivetrackr.com/` (index.html)
- **User Management**: `https://admin.5ivetrackr.com/user-management.html`
- **Referee Registration**: `https://admin.5ivetrackr.com/referee-registration.html`

### Development

This webpage serves two main purposes:
1. **Public Website**: Marketing and subscription management
2. **Admin Dashboard**: User management and administrative functions

### Integration

- **Webapp Communication**: Links to `https://www.webapp.5ivetrackr.com/`
- **API Integration**: Uses hosted database for user management
- **Cross-Platform**: Coordinates with mobile apps through webapp

This clean structure separates public content from administrative functions while maintaining easy navigation and deployment.
