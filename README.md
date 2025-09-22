
🗺️ MapNav Pro - Advanced Google Maps Clone
A feature-rich, interactive mapping and navigation web application built with vanilla JavaScript and Leaflet.js. MapNav Pro replicates core Google Maps functionality with a clean, modern interface and advanced features like multi-stop routing, live simulation, and dark mode.

https://cool-khapse-2fa5ec.netlify.app/

<img width="1855" height="939" alt="image" src="https://github.com/user-attachments/assets/86fc880f-e5df-425a-b029-98918e5eb178" />


✨ Features
🌍 Interactive Mapping: Powered by Leaflet.js with OpenStreetMap tiles for a seamless mapping experience.

🔍 Smart Search & Geocoding: Real-time location search and suggestions using the Nominatim (OpenStreetMap) API.

🛣️ Advanced Routing & Navigation: Calculate optimal routes for driving, cycling, and walking using the OSRM routing engine.

📍 Multi-Stop Waypoints: Add, remove, and dynamically drag-and-drop multiple destinations to customize your journey.

🧭 Live Navigation Simulation: Simulate a real-time GPS journey along the calculated route with turn-by-turn instructions.

🌙 Dark Mode: Toggle between light and dark themes for comfortable viewing at any time.

📱 Fully Responsive Design: Works flawlessly on desktop, tablet, and mobile devices.

ℹ️ Live Data: Integrated weather widget and simulated traffic information for enhanced trip planning.

⌨️ Keyboard-Friendly: Triple-click on the map to quickly add new waypoints.

🛠️ Tech Stack
Frontend: Vanilla JavaScript, HTML5, CSS3

Mapping Library: Leaflet.js

Routing Engine: OSRM via Leaflet Routing Machine

Geocoding API: Nominatim (OpenStreetMap)

Icons: Font Awesome

Drag & Drop: SortableJS

🚀 Getting Started
Prerequisites
Just a modern web browser! All dependencies are loaded via CDN.

Installation & Usage
Clone the repository

bash
git clone https://github.com/your-username/mapnav-pro.git
cd mapnav-pro
Open the application

Simply open the index.html file in your web browser.

For the best experience, serve it with a local server:

bash
# Using Python 3
python -m http.server 8000
# Navigate to http://localhost:8000
Start Navigating

Search: Use the search bar to find a location.

Add Waypoints: Click the "+" button or triple-click anywhere on the map to add a destination.

Choose Transport Mode: Select between driving, cycling, or walking.

Simulate: Click the "Play" button to start a simulation of your route.

📁 Project Structure
text
mapnav-pro/
├── index.html          # Main application file
├── README.md           # Project documentation
└── assets/             # (Optional) Directory for images, icons, etc.
🔧 How to Use
Searching: Type an address or place name into the search bar. Select a result from the dropdown to add it as a waypoint.

Adding Waypoints: Click the "+" button next to the search bar or triple-click on any point on the map.

Planning a Route: Add at least two waypoints (A and B). The route will calculate automatically.

Changing Transportation Mode: Click the car, bike, or walk icons in the sidebar to recalculate the route.

Reordering Waypoints: Drag and drop items in the waypoints list to reorder your trip.

Simulating Navigation: With a route calculated, click the "Play" button to start a simulation. Follow the turn-by-turn instructions in the navigation header.

🧪 Key Technical Implementation Details
State Management: Handled complex application state (user location, waypoints, routes, UI mode) using vanilla JavaScript objects and DOM manipulation.

API Integration: Successfully orchestrated multiple external APIs (OSRM for routing, Nominatim for geocoding) with custom error handling and fallbacks.

Performance: Optimized Leaflet map rendering and layer management for smooth interaction with multiple markers and large polylines.

UI/UX: Designed and implemented a custom, responsive user interface from scratch with CSS Grid/Flexbox and smooth animations.

👨‍💻 Developer
Sivaprakasam - View GitHub
