# Web Proxy Application

## Overview
A client-side web proxy application built as a single HTML file that allows users to browse websites through proxy services. The app features a tabbed interface similar to a web browser and uses services like AllOrigins to bypass CORS restrictions.

## Project Structure
- `Proxy.html` - Main application file containing HTML, CSS, and JavaScript
- Single-file application with no build dependencies
- Pure client-side implementation

## Key Features
- Tabbed browsing interface
- Multiple proxy service fallback system (AllOrigins, CorsAnywhere, CodeTabs)
- URL rewriting for proper asset loading
- Navigation history (back/forward buttons)
- Search functionality (fallback to Google search)
- Responsive design with dark theme

## Technical Details
- **Frontend**: Pure HTML/CSS/JavaScript (no frameworks)
- **Proxy Services**: Uses external CORS proxy services
- **Architecture**: Single-page application
- **Port**: Configured to run on port 5000 for Replit environment

## Proxy Services Used
1. AllOrigins (primary)
2. CorsAnywhere (fallback)  
3. CodeTabs (fallback)

## Setup Instructions
1. Serve the HTML file using a simple HTTP server
2. Access through browser on port 5000
3. No build process or dependencies required

## Recent Changes
- Initial import from GitHub repository (September 16, 2025)
- Configured for Replit environment with port 5000 setup
- Security improvements:
  - Removed allow-same-origin from iframe sandbox to prevent security vulnerabilities
  - Fixed proxy service consistency between main app and injected scripts
  - Removed unreliable CORS-Anywhere service, keeping AllOrigins and CodeTabs only
- Renamed Proxy.html to index.html for standard web serving

## User Preferences
- None documented yet

## Project Architecture
- Single HTML file application
- Client-side proxy using external services
- No backend components required
- Stateless application design
