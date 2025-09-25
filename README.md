# Hazard Map App

A simple mobile-friendly Progressive Web App (PWA) to map hazards on a floorplan.  
Built with **HTML, CSS, JavaScript, Leaflet.js**, and uses **localStorage** for persistence.  

---

## 🚀 Features

### ✅ Current Features
- **Upload a floorplan** (image) and place it on the map.  
- **Add hazard markers**:
  - Multiple shapes: circle, square, triangle.  
  - Multiple colors.  
  - Draggable markers.  
  - Optional notes for each marker.  
- **Persistent storage**: floorplan and markers are saved locally and restored on reload.  
- **Sidebar controls**:
  - Upload new floorplan.  
  - Save current state as a **named project**.  
  - List all saved projects, load or delete them.  
  - Export project as JSON file.  
  - Import project from JSON file.  
- **Mobile-first UI**:
  - Sidebar slides in/out.  
  - Floating “+” button for adding hazards.  
  - Clean dark theme with orange highlights.  
  - Tap outside shape/color picker to close it.  

---

### 🛠 Planned / Optional Features
- **Attach photos to markers** (with thumbnails shown in notes).  
- **Advanced sharing**:
  - Export/import already works.  
  - Future option: real-time sync across devices via Firebase or Supabase.  

---

## 📂 Project Structure

```text
index.html        # Main app (UI + logic)
style.css         # Styling (dark theme + orange accents)
manifest.json     # PWA manifest (for installable app)
service-worker.js # Service worker (offline support)
