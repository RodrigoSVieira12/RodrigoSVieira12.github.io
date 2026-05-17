# Personal Portfolio — Rodrigo Santos Vieira

This repository contains the source code for my personal portfolio website.

The site serves as a central place to present my academic background, research, professional experience, and projects in Biomedical Engineering, Bioinformatics, and AI.

🌐 **Live site:** [rodrigosvieira12.github.io/rodrigo-portfolio](https://rodrigosvieira12.github.io/rodrigo-portfolio)

## About me

MSc student in Biomedical Engineering at **KU Leuven** (Bioinformatics & AI track), with a BSc from **Instituto Superior Técnico**, Lisbon. Interested in the intersection of healthcare, data, and engineering.

## Tech stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, CSS Grid, Flexbox, responsive design
- **Vanilla JavaScript** — IntersectionObserver for scroll animations, no frameworks
- **Google Fonts** — Cormorant Garamond, Cinzel, DM Sans

No build step, no dependencies — pure static site.

## Project structure

```
rodrigo-portfolio/
├── index.html          # Main page
├── README.md           # This file
├── LICENSE             # MIT License
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # Scroll reveal + nav behaviour
└── images/
```

## Running locally

Because browsers block loading external files (CSS/JS/images) from `file://` URLs for security reasons, you need a small local server. Pick one:

**Python (built-in on Mac/Linux):**
```bash
cd rodrigo-portfolio
python3 -m http.server 8000
```
Then open <http://localhost:8000>.

**VS Code:** install the **Live Server** extension, right-click `index.html` → "Open with Live Server".

**Node.js:**
```bash
npx serve .
```

## Deployment

The site is deployed via **GitHub Pages**:
1. Push to `main` branch
2. Repo Settings → Pages → Source: `main` / root
3. Wait ~1 minute, the site is live at `https://<username>.github.io/<repo>`

## Contact

- 📧 [rodrigosvieira.rsv@gmail.com](mailto:rodrigosvieira.rsv@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/rodrigo-santos-vieira12)
- 💻 [GitHub](https://github.com/RodrigoSVieira12)

## License

MIT — see [LICENSE](LICENSE).
