# UNESCO World Heritage Sites 3D Globe Map

This interactive 3D globe map visualizes UNESCO World Heritage Sites, allowing users to explore cultural, natural, and mixed heritage locations worldwide.

## Features
- 3D globe projection with terrain and atmosphere effects.
- Interactive markers with hover enlargement and click popups.
- Filterable by site type (Cultural, Natural, Mixed) and status (In Danger).
- Modern glassmorphism UI with animations.
- Mobile-responsive design with touch support.

## Data Source and Rights

The dataset used in this project is the "World Heritage Site List" provided by UNESCO IHP-WINS.

- **Creator**: Chloé Meyer (2024)
- **Title**: World Heritage Site List [Data set]
- **Publisher**: UNESCO IHP-WINS
- **DOI**: [https://doi.org/10.63253/qblhcalw](https://doi.org/10.63253/qblhcalw)
- **License**: Creative Commons Attribution Share-Alike (CC BY-SA)
- **Rights Statement**: This dataset is open data under the Creative Commons Attribution Share-Alike license. You are free to share and adapt the material as long as you give appropriate credit to the original creator and distribute your contributions under the same license.

For more information, visit the [UNESCO IHP-WINS dataset page](https://ihp-wins.unesco.org/dataset/unesco-world-heritage-sites).

## Usage
1. Run a local server: `python -m http.server 8000`
2. Open `http://localhost:8000/index.html` in your browser.
3. Use the menu to filter sites.
4. Click on markers for details.

## Technologies
- MapLibre GL JS
- PapaParse for CSV handling
- HTML/CSS/JS
