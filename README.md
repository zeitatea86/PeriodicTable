# Periodic Table of Elements

An interactive periodic table built with vanilla HTML, CSS, and JavaScript.

## Features

- All 118 elements with atomic number, symbol, name, and atomic mass displayed on each cell
- Color-coded by element category (Nonmetal, Noble gas, Alkali metal, etc.)
- Text color indicates physical state at room temperature — red for gas, blue for liquid, black for solid
- Hover over any legend label to highlight only that category
- Hover over any state button (Gas / Liquid / Solid) to highlight only elements of that state
- Click any element to open a detail popup with all 17 properties
- Search bar with autocomplete to find and highlight any element by name

## How to open

No build step or server required. Just open `index.html` directly in a browser:

```
double-click index.html
```

Or from the terminal:

```bash
xdg-open index.html        # Linux
open index.html            # macOS
start index.html           # Windows
```

## Project structure

```
PeriodicTable/
├── index.html          # Main entry point
├── css/
│   └── styles.css      # All styles
├── js/
│   └── chemistry.js    # Element data + all interactive logic
├── images/
│   ├── chemistry.jpg   # Background image
│   ├── gas.jpg         # Gas state button background
│   ├── liquid.jpg      # Liquid state button background
│   ├── solid.jpg       # Solid state button background
│   ├── molecule.png    # Logo image
│   └── favicon.ico     # Browser tab icon
└── v1/                 # Original draft (kept for reference)
```

## Dependencies

- [jQuery 3.7.1](https://jquery.com/) — used for the search autocomplete widget
- [jQuery UI 1.13.2](https://jqueryui.com/) — autocomplete component
- [List.js 2.3.1](https://listjs.com/) — loaded but available for future filtering use

All dependencies are loaded from CDN, no installation needed.
