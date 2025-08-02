# QUICK REFERENCE - Camera Manual Vault
Generated: 8/2/2025, 12:20:31 AM

## Project Overview
- **Total Files**: 47
- **Total Lines**: 12,100
- **Primary Language**: JavaScript
- **Framework**: Express.js + SQLite

## Key Files & Locations

### Frontend Pages
- **attribution.html**: /public/attribution.html
- **camera-blog.html**: /public/camera-blog.html
- **camera-detail.html**: /public/camera-detail.html
- **camera-finder.html**: /public/camera-finder.html
- **cameras.html**: /public/cameras.html
- **dmca.html**: /public/dmca.html
- **index.html**: /public/index.html
- **legal.html**: /public/legal.html
- **login.html**: /public/login.html
- **privacy.html**: /public/privacy.html
- **productions.html**: /public/productions.html
- **search.html**: /public/search.html
- **terms.html**: /public/terms.html

### Core Scripts
- **Server**: /server.js
- **Scrapers**: /continuous-scraper.js, /ultimate-scraper.js
- **Package Config**: /package.json

### Styling
- **Main CSS**: /public/css/main.css (429 lines)
- **CSS Variables**: 28 defined

### API Endpoints Summary
- GET /api/cameras
- GET /api/camera/:id
- GET /api/search
- GET /api/stats
- GET /api/image-proxy
- GET /images/cameras/:filename
- POST /api/camera-finder
- GET /camera/:id
- GET /camera-blog
- GET /privacy
- GET /terms
- GET /dmca
- GET /attribution
- GET /legal

## Recent Changes
No recent commits

## Quick Commands
```bash
# Start server
npm start

# Run scraper
node continuous-scraper.js

# Generate structure
node scripts/generate-structure.js ../cmv-structure
```

## File Type Distribution
- .ejs: 16 files
- .html: 13 files
- .js: 10 files
- .md: 3 files
- .json: 2 files
- .db: 1 files
- .css: 1 files
- .jpg: 1 files

## Largest Files
- public/cameras.html: 68.91 KB
- public/images/camera-placeholder.jpg: 68.50 KB
- public/search.html: 32.26 KB
- public/camera-detail.html: 31.09 KB
- public/productions.html: 25.91 KB
- scripts/generate-structure.js: 23.65 KB
- public/camera-finder.html: 23.35 KB
- public/camera-blog.html: 23.29 KB
- auto-setup-ejs.js: 22.42 KB
- views/pages/index-full.ejs: 17.21 KB
