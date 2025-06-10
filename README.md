# Kolkata Compass

[https://kolkatacompass.netlify.app/]


✈️ Responsive Travel Guide for Kolkata
Developed a dynamic and responsive travel guide website for Kolkata using HTML, CSS, and JavaScript.
Integrated DistanceTo API (via Rapid API) and OpenWeather API to provide users with real-time flight durations, distances, and live weather updates.


## Tech Stack

- HTML5
- CSS3
- JavaScript
- DistanceTo
- OpenWeather API


🌆 Design

<div>
  <img src=".assests/screenshots/1_HomePage.jpg">
![Home Page](screenshots/1_HomePage.jpg)
  
</div>

- Widget-based hero section showing current time and weather in Kolkata, flight duration & distance, and navigation menu
- Fully responsive design with a clean, muted color palette
- Utilizes advanced CSS grid and flexbox layouts for consistent alignment across all screen sizes
- Subtle transitions and hover effects for buttons and images
- Horizontally scrollable card system for highlighting top destinations in and around Kolkata


📊 Data Integration

- Live weather data via OpenWeather API
- Flight time and distance to Kolkata using the DistanceTo API
- Text content curated with help from ChatGPT
- Hotel and neighborhood information sourced from .json files authored and compiled manually


🔄 Interactive Features

- Search functionality for 3-letter airport codes to get real-time flight info to Kolkata
- Geolocation support: Automatically detects user location to compute flight time and distance to Kolkata
- ‘See Map’ button in the Top Destinations section toggles an iframe map view for each location
- Hotel guide toggle: Switch between top hotels to view corresponding details (image, address, phone, booking link)


🛠️ Under the Hood

- Uses JavaScript’s Date() object to show current time in Kolkata
- Custom hover effects using mouseenter and mouseleave events for menu buttons
- Dynamic weather icons with proper alt attributes based on current weather data
- All external data fetched via fetch() and rendered dynamically into the DOM
- Stores last searched airport using localStorage for improved UX
- Dynamically renders structured content (hotels, areas, etc.) from .json files
