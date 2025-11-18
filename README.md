# ACSAHE Website

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://facundo-pfeffer.github.io/ACSAHE.github.io/)
[![License](https://img.shields.io/badge/License-CCA%203.0-green.svg)](LICENSE.txt)
[![Award](https://img.shields.io/badge/Award-1st%20Place%20COLEIC%202024-gold.svg)](https://www.coleicoficial.com/)

Official landing page for **ACSAHE** (Análisis de Secciones de Hormigón Armado y Estructuras) - A free software for structural concrete section analysis.

## Award-Winning Project

**First Place** at COLEIC 2024 (Latin American Congress of Civil Engineering Students)

## About ACSAHE

ACSAHE generates interaction diagrams of combined axial-force/biaxial-bending for structural concrete sections under ACI 318-19(22)'s Chapter 22 hypothesis. The tool offers complete flexibility to explore and analyze all cross-section possibilities, including those with prestressed reinforcement.

**Developed by:**
- Facundo Leguizamón Pfeffer
- Dr. Oscar Möller

**Institution:** Institute of Applied Mechanics and Structures (IMAE), Universidad Nacional de Rosario, Argentina

## Features

- Analysis of arbitrary concrete sections
- 3D interaction diagrams
- Biaxial bending analysis
- Fast computation
- Support for prestressed reinforcement
- Free and open-source

## Live Demo

**Website:** [https://facundo-pfeffer.github.io/ACSAHE.github.io/](https://facundo-pfeffer.github.io/ACSAHE.github.io/)

### Interactive Examples

- **Example I:** [Box-girder bridge section (3D)](https://facundo-pfeffer.github.io/ACSAHE.github.io/pages/examples/box-girder.html)
- **Example II:** [Circular Pile (3D)](https://facundo-pfeffer.github.io/ACSAHE.github.io/pages/examples/pile.html)
- **Example III:** [Final Design Homework 10](https://facundo-pfeffer.github.io/ACSAHE.github.io/pages/examples/hw10-pm.html)

## Project Structure

```
ACSAHE.github.io/
├── index.html                      # Main landing page
├── pages/                          # Secondary pages
│   ├── acknowledgments.html        # Acknowledgments page
│   └── examples/                   # Example demonstrations
│       ├── box-girder.html         # Box girder example
│       └── pile.html               # Pile example
├── assets/
│   ├── css/                        # Stylesheets
│   ├── js/                         # JavaScript files
│   ├── fonts/                      # Font files (Font Awesome)
│   └── data/
│       └── plotly/                 # Interactive Plotly visualizations
│           ├── box-girder-section.html
│           └── box-girder-interaction.html
├── images/
│   ├── diagrams/                   # Technical diagrams
│   ├── photos/                     # Event and team photos
│   └── icons/                      # Logo and icons
├── docs/                           # Project documentation
│   ├── README.md                   # Detailed documentation
│   └── CLEANUP_SUMMARY.md          # Repository cleanup history
├── .gitignore                      # Git ignore rules
└── LICENSE.txt                     # License information
```

## Technologies Used

- **HTML5/CSS3** - Modern web standards
- **JavaScript** - Interactive functionality
- **Plotly.js** - Interactive 3D visualizations
- **Font Awesome** - Icons and symbols
- **jQuery** - DOM manipulation

## Local Development

To run the website locally:

```bash
# Clone the repository
git clone https://github.com/Facundo-Pfeffer/ACSAHE.github.io.git

# Navigate to the directory
cd ACSAHE.github.io

# Open in browser
# Simply open index.html in your web browser
```

For development with live reload, you can use a simple HTTP server:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server

# Then visit: http://localhost:8000
```

## Making Changes

1. Edit HTML/CSS/JS files as needed
2. Test locally by opening `index.html` in a browser
3. Commit changes to the `main` branch
4. Push to GitHub (automatically deploys via GitHub Pages)

## Recognitions

- **1st Place** - COLEIC 2024 (Latin American Congress of Civil Engineering Students)
- **Published** - 30th JJI (Young Researchers Conference), Paraguay
- **Presented** - 15th CONEIC (National Conference of Civil Engineering Students), Argentina
- **Featured** - TELEFÉ News, Argentina

## Contact

**Facundo Leguizamón Pfeffer**
- Email: [facundo.pfeffer@berkeley.edu](mailto:facundo.pfeffer@berkeley.edu)
- LinkedIn: [linkedin.com/in/facundopfeffer](https://www.linkedin.com/in/facundopfeffer/)
- GitHub: [github.com/Facundo-Pfeffer](https://github.com/Facundo-Pfeffer)
- Location: Instituto de Mecánica Aplicada y Estructuras (IMAE), Rosario, Argentina

## License

- **Website Code:** Based on "Massively" template by [HTML5 UP](https://html5up.net) - CCA 3.0 license
- **ACSAHE Software:** Refer to the main software repository for licensing information

## Design Credits

Website design based on the "Massively" template by [HTML5 UP](https://html5up.net)
- Free for personal and commercial use under the [CCA 3.0 license](https://html5up.net/license)

---

*Made for the structural engineering community*
