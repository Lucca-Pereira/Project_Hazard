# Hazard Map (PWA)

Hazard Map is a Progressive Web App (PWA) for creating and sharing hazard overlays on custom floorplans.  
Built with Leaflet.js, it allows users to upload a floorplan image, place hazard markers (different shapes and colors), save and load projects, and share them via import/export.

## Features
- Custom hazard markers: circle, square, or triangle in multiple colors  
- Upload a floorplan image as the map background  
- Save and load multiple projects locally using browser storage  
- Import and export projects as JSON files  
- Installable as a PWA (works offline on desktop and mobile)  
- Sidebar interface for project management and hazard editing  
- Dark theme with orange highlight

## Tech Stack
- [Leaflet.js](https://leafletjs.com/) for interactive maps  
- HTML, CSS, and JavaScript (no backend required)  
- LocalStorage for persistence  
- Service Worker for offline caching  
- PWA manifest for installability

## Usage
1. Open the app: [https://lucca-pereira.github.io/Project_Hazard/](https://lucca-pereira.github.io/Project_Hazard/)  
2. Upload a floorplan image  
3. Add hazard markers by selecting shape and color, then clicking on the map  
4. Save your project with a name  
5. Export or import projects as JSON to share or reuse  
6. Install as an app on desktop or mobile for standalone use

## Deployment
- Hosted on GitHub Pages  
- PWA enabled with manifest and service worker  
- Tested install on Chrome (desktop and mobile)
