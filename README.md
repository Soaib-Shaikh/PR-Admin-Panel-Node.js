# PR-Admin-Panel-Node.js

## Overview
A Node.js-based admin panel using Express and EJS for server-side rendering. The project provides a responsive UI for managing tables, forms, and other admin features.

Link Here:- https://pr-admin-panel-node-js.onrender.com

## Technologies Used
- **Node.js**: JavaScript runtime environment
- **Express.js**: Web framework for Node.js
- **EJS**: Templating engine for server-side rendering
- **Bootstrap**: Frontend CSS framework (via public assets)
- **jQuery**: JavaScript library (via public assets)
- **DataTables**: Table management and display
- **FullCalendar**: Calendar UI
- **Toastr**: Notifications
- **Other JS/CSS plugins**: Various UI enhancements (multicheck, gritter, sparkline, etc.)

## Features
- Dashboard homepage
- Table management page
- Basic form page
- Form wizard page
- Static asset serving (CSS, JS, images)
- Modular EJS views for easy customization

## Folder Structure
```
index.js                # Main server file
package.json            # Project metadata and dependencies
public/                 # Static assets (CSS, JS, images)
  assets/               # JS/CSS plugins and libraries
    extra-libs/         # Additional libraries (calendar, DataTables, gritter, multicheck, sparkline)
    images/             # Image assets (logos, backgrounds, user images)
    libs/               # Core libraries (bootstrap, chart, datatables, flot, etc.)
views/                  # EJS templates
  index.ejs             # Main dashboard view
  pages/                # Sub-pages (footer, forms, tables, header)
  partials/             # Reusable partial templates
```

## Getting Started
1. Install dependencies:
   ```
   npm install
   ```
2. Start the server:
   ```
   node index.js
   ```
3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage
- Visit `/` for the dashboard
- Visit `/tables` for table management
- Visit `/form-basic` for basic form
- Visit `/form-wizard` for form wizard

## Customization
- Modify EJS templates in `views/` for UI changes
- Add or update static assets in `public/`
