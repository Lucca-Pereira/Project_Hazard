Hazard Map App

A simple mobile-friendly Progressive Web App (PWA) to map hazards on a floorplan.
Built with HTML, CSS, JavaScript, Leaflet.js, and uses localStorage for persistence.

🚀 Features
✅ Current Features

Upload a floorplan (image) and place it on the map.

Add hazard markers:

Multiple shapes: circle, square, triangle.

Multiple colors.

Draggable markers.

Optional notes for each marker.

Persistent storage: floorplan and markers are saved locally and restored on reload.

Sidebar controls:

Upload new floorplan.

Save current state as a named project.

List all saved projects, load or delete them.

Export project as JSON file.

Import project from JSON file.

Mobile-first UI:

Sidebar slides in/out.

Floating “+” button for adding hazards.

Clean dark theme with orange highlights.

Tap outside shape/color picker to close it.

🛠 Planned / Optional Features

Attach photos to markers (with thumbnails shown in notes).

Advanced sharing:

Export/import already works.

Future option: real-time sync across devices via Firebase or Supabase.

📂 Project Structure
index.html       # Main app (UI + logic)
style.css        # Styling (dark theme + orange accents)
manifest.json    # PWA manifest (for installable app)
service-worker.js# Service worker (offline support)

🖥 How to Use

Open the app in a browser (mobile or desktop).

Upload a floorplan image.

Tap + → select shape + color → tap on floorplan to place marker.

Drag markers or add notes as needed.

Save your project with a name (in the sidebar).

Use Export to share as JSON, Import to load a shared project.

📱 Install as an App

Since this is a PWA, you can:

On Chrome/Android: Tap menu → Add to Home screen.

On iOS Safari: Share → Add to Home Screen.

🆓 Technology & Costs

100% frontend → runs fully offline.

Uses browser localStorage for saving data.

No backend required, so completely free to use and share.

👉 This makes it a good balance between simplicity (everything local/offline) and shareability (via export/import JSON).
