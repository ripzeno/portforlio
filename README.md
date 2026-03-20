# Alex Morgan — Portfolio Website

A professional portfolio website built with HTML5, CSS3, and vanilla JavaScript. Designed to showcase skills, projects, and contact information in a visually distinctive, fully responsive layout.

---

## Website Structure

```
portfolio/
├── index.html              # Home page — Hero, featured projects, about teaser, CTA
├── pages/
│   ├── about.html          # About page — Bio, skills grid, experience timeline
│   ├── projects.html       # Projects page — Filterable project showcase
│   └── contact.html        # Contact page — Contact form + details
├── css/
│   └── style.css           # All styles (variables, components, responsive breakpoints)
├── js/
│   └── main.js             # Navigation, scroll effects, filter logic, form handling
└── README.md
```

---

## Pages & Navigation

The site includes four pages linked through a persistent navigation bar:

- **Home (`index.html`)** — Full-screen hero section, animated skills marquee, featured project cards, and a statistics teaser.
- **About (`pages/about.html`)** — Developer biography, a visual skills grid, and a chronological career timeline.
- **Projects (`pages/projects.html`)** — A filterable grid of six projects, each with technology tags, descriptions, and links to GitHub repositories and live demos.
- **Contact (`pages/contact.html`)** — Contact details, availability status, and a functional enquiry form.

---

## Features

**Design & Aesthetics**
- Editorial typographic style using Playfair Display (display), DM Mono (monospaced labels), and DM Sans (body)
- CSS custom properties for a consistent colour palette across all pages
- Diagonal background shapes, grid overlays, and gradient placeholder artwork
- CSS-only animations: page entrance (`@keyframes fadeUp`), a marquee skills strip, and a scanning scroll indicator

**Interactivity**
- Sticky navbar that transitions on scroll (transparent → frosted glass)
- Mobile hamburger menu with animated open/close state
- IntersectionObserver scroll-reveal for cards, stats, and timeline items
- JavaScript-powered project category filter (All / Web Apps / Mobile / Design / Open Source)
- Contact form with submission feedback and auto-reset

**Responsiveness**
Three responsive breakpoints via media queries:
- `≤ 1024px` — Single-column layouts for project and about grids
- `≤ 768px` — Mobile navigation drawer, reduced padding, stacked footer
- `≤ 480px` — Adjusted hero typography and single-column CTA buttons

---

## Hosting

The site is hosted on **GitHub Pages**. To deploy your own copy:

1. Fork or clone this repository.
2. Go to **Settings → Pages** in your GitHub repository.
3. Set the source to the `main` branch, root directory.
4. GitHub Pages will publish the site at `https://<username>.github.io/<repo-name>`.

All asset paths use relative URLs, so the site works correctly from any subdirectory.

---

## Customisation

To adapt this portfolio for personal use, update the following:

- Replace "Alex Morgan" and personal details throughout all four HTML files.
- Update project names, descriptions, tags, and links in `projects.html` and `index.html`.
- Swap placeholder GitHub/LinkedIn/email links in navigation, footer, and contact page.
- Adjust the colour palette in the `:root` block at the top of `css/style.css`.

---

## Technologies Used

HTML5 · CSS3 (Custom Properties, Grid, Flexbox, Animations) · Vanilla JavaScript (ES6+) · Google Fonts · GitHub Pages
