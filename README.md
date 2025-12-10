# ScientificIndian

> A small static website collecting laboratory experiments, equipment lists, and educational resources for undergraduate-level science labs.

## Overview

ScientificIndian is a static website built with HTML, CSS, and client-side JavaScript. It organizes lab materials, equipment, images, and datasets into separate pages for easy browsing by students and instructors.

## Features

- Organized lab pages (e.g., `labs/`): experiment write-ups, images, and resources.
- Equipment catalog in `equipments/` with styles and layouts.
- A small dataset file in `data/lab-data.js` for use in pages.
- Fully static — no server-side dependencies.

## Quick Start

Prerequisites:
- A modern web browser (Chrome, Edge, Firefox)
- Optional: Python (for a simple local server) or Node.js (for static server tools)

Local preview (recommended):

1. Open the project directory in your terminal or PowerShell:

```
cd 'D:\Piyusha\Project\WebDev\ScientificIndia'
```

2a. Using Python 3 built-in server:

```
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

2b. Or using the `serve` package (Node.js):

```
npm install -g serve
serve -s .
```

2c. Or use VS Code Live Server extension: right-click `index.html` → "Open with Live Server".

## Project Structure

- `index.html` — site entry page
- `style.css` — global styles
- `assets/` — static assets (icons, etc.)
- `data/lab-data.js` — sample data for pages
- `equipments/` — equipment listing pages and `equipment.css`
- `labs/` — lab pages and images grouped by topic
  - `labs/images/` — lab illustrations and photos

(The full repository tree is present in the project root.)

## Contributing

- Fork the repository and create a topic branch for your change.
- Make small, focused commits and a clear PR description.
- For content changes (lab instructions, images), ensure accuracy and include sources.

Suggested workflow:

```
git checkout -b fix/typo-in-lab
git add <files>
git commit -m "Fix typo in lab heat.html"
git push origin fix/typo-in-lab
# Open a Pull Request on GitHub
```

## Deployment

You can host this static site on GitHub Pages (enable Pages in repository settings and select the `main` branch root) or any static host (Netlify, Vercel, Firebase Hosting).

## License

This project is available under the MIT License — add a `LICENSE` file to make it explicit.

## Contact

Project maintained by the repository owner. For questions or contributions, open an issue or a pull request on the GitHub repository.

---

If you'd like, I can:

- commit and push this `README.md` for you, or
- customize the README with a logo, badges, or a live demo link.

Tell me which you'd like next.
