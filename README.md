# places

# Places Visited — Curated Interactive Map

An elegant interactive map showcasing curated places visited across cities using Leaflet.js.

Designed with:
- luxury editorial aesthetics
- animated custom pins
- clustering
- searchable locations
- responsive mobile layout
- smooth micro-interactions


---

## Features

- Interactive map with clustering
- Elegant gold-themed custom markers
- Search locations instantly
- Filter by city/metro
- Responsive mobile experience
- Smooth animations
- Lightweight static website
- Deployable via GitHub Pages

---

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- Leaflet.js
- Leaflet MarkerCluster

---

## Project Structure

```txt
places-visited-map/
├── index.html
├── data/
│   └── places.json
├── assets/
│   └── preview.png
├── LICENSE
├── .gitignore
└── README.md
```

---

## Setup

Clone the repository:

```bash
git clone https://github.com/yourusername/places-visited-map.git
```

Open locally:

```bash
cd places-visited-map
```

Then simply open:

```txt
index.html
```

Or run with VS Code Live Server.

---

## Deploy on GitHub Pages

1. Push the repo to GitHub
2. Open:
   - Settings
   - Pages
3. Under "Build and deployment":
   - Source → Deploy from branch
   - Branch → main
4. Save

Your site will be live at:

```txt
https://yourusername.github.io/places-visited-map/
```

---

## Customization

### Add Places

Edit:

```txt
/data/places.json
```

Format:

```json
[
  {
    "name": "Cafe Name",
    "url": "https://maps.google.com",
    "metro": "Bengaluru",
    "area": "Indiranagar",
    "lat": 12.9716,
    "lng": 77.5946
  }
]
```

---

## Credits

- Leaflet.js
- OpenStreetMap
- Google Fonts

---

## License

MIT
