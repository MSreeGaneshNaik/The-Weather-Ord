✨ Weather Orb
Weather Orb is a fully client-side, interactive 3D visualization that transforms raw meteorological data into an engaging, intuitive “orb” display. Built with pure HTML5, CSS3, and modern JavaScript (ES6+), the orb dynamically adapts its color, texture, lighting, and animation patterns to reflect real-time weather conditions fetched from the OpenWeatherMap API.

🌤️ Motivation & Overview
Understanding weather at a glance can be challenging when buried in numbers—temperature, humidity, wind speed, and condition codes. Weather Orb addresses this by:

Turning numerical data into a single, glanceable interface

Using 3D transforms and subtle animations to convey mood (sunny, cloudy, rainy, stormy)

Offering a playful, interactive experience: drag to rotate, hover for details

This project demonstrates mastery of:

API integration (fetching and parsing JSON)

CSS 3D transforms (perspective, rotateX, rotateY) and animations (@keyframes)

Event-driven scripting (requestAnimationFrame, mouse events)

Responsive design without any third-party libraries

🚀 Key Features
Real-Time API Integration

Fetches temperature, humidity, weather description, and icon from OpenWeatherMap

Auto-updates every 10 minutes (configurable)

3D Orb Visualization

High-performance rendering via CSS-only transforms

Smooth rotation controlled by mouse/touch drag or arrow keys

Condition-Driven Styling & Animation

Sunny: Warm, golden glow and gentle pulsation

Cloudy: Soft gray hues with slow, floating “cloud” overlays

Rainy: Subtle ripple effects and intermittent “drip” animations

Stormy: Rapid flickers and deep blue-purple gradients

Responsive & Lightweight

Automatically scales to fit any viewport (desktop, tablet, mobile)

No dependencies—under 30 KB of combined HTML/CSS/JS

Modular & Extensible

Simple theming via CSS variables (--orb-color, --glow-intensity)

Pluggable animation functions for adding new weather states

⚙️ Tech Stack & Architecture
HTML5

Semantic structure: <section class="weather-orb">, <canvas> fallback support

CSS3

Custom properties for easy theming

3D transforms and @keyframes for animations

Flexbox for centering and layout

JavaScript (ES6+)

fetch() API to retrieve weather data

async/await for clean asynchronous code

requestAnimationFrame for smooth, performant animations

Modular code split into classes (WeatherService, OrbRenderer, UIController)

🎨 Customization
Themes: Edit CSS variables at the top of styles.css to switch palettes.

Update Interval: Change the REFRESH_INTERVAL constant in main.js (default 600 000 ms).

New Conditions: Extend OrbRenderer.animateForCondition(condition) with additional animation logic.

🤝 Contributing
Contributions are welcome! Feel free to:

Report issues or request features via GitHub Issues

Fork the project and submit pull requests

Share your own texture maps or animation snippets
