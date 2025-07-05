# NextGen Terminal 2025

A sleek, interactive CLI with 3D visualizations, built with HTML, CSS, and JavaScript.

## Features

- **Interactive CLI**: Commands like `help`, `weather`, `stock`, `theme`, `mkdir`, `ls`, `cd`, `touch`, `cat`.
- **3D Visualizations**: Animations for `date`, `weather`, `stock`, `tree` using Three.js.
- **Themes**: Default, light, gold, silver.
- **Command History & Aliases**: Save and recall commands, set aliases.
- **Virtual Filesystem**: Manage files and folders.
- **Responsive**: Optimized for desktop and mobile.

## Setup

1. Download `index.html`.
2. Open in a browser.
3. Type `help` for commands.

## Key Commands

- `help`: List commands.
- `theme <default/light/gold/silver>`: Switch themes.
- `weather <city>`: Mock weather data with visualization.
- `stock <symbol>`: Mock stock prices with chart.
- `tree`: 3D filesystem visualization.
- `viz on/off/clear`: Control visualization persistence.

## Dependencies

- [Three.js](https://threejs.org/)
- [GSAP](https://greensock.com/gsap/)
- [Chart.js](https://www.chartjs.org/)
- [IBM Plex Mono](https://fonts.google.com/)

## Notes

- Uses mock data for `weather` and `stock`.
- Stores data in `localStorage`.
- Mobile-optimized with reduced particles.

## Author

Yash Nigam