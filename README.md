# Danbi Kim Personal Website

This repository contains my personal website and portfolio, published through GitHub Pages at `iamdanbi.github.io`.

The site is a static HTML/CSS website for presenting who I am, what I study, and what I build. It includes a short personal introduction, academic background, selected projects, contact links, and a downloadable resume. The website is intentionally lightweight and handmade, with a focus on direct navigation and personal expression rather than a generic template.

## Overview

This website serves as a public home for my work as an independent researcher and builder. It brings together:

- Academic background and research interests
- Selected projects in quantitative research, mathematical modeling, software, and creative experiments
- Personal writing and exploratory materials
- Resume and contact information
- Visual elements that reflect my own taste, process, and way of thinking

The initial visual design was created in Figma and then implemented as HTML/CSS with the help of Codex. The current codebase is simple by design, making it easy to inspect, modify, and extend without requiring a complex build system.

Google Analytics 4 is integrated for basic traffic and visitor analytics.

## Design Philosophy

The website is inspired by brutalist web design, experimental personal websites, and interactive web experiences.

Rather than aiming for polished corporate aesthetics, the design emphasizes simplicity, individuality, exploration, and a handcrafted feel. I wanted the site to feel like a personal space: direct, slightly rough-edged, and shaped by curiosity. The layout, imagery, typography, and interactions are meant to invite exploration while keeping the structure readable and usable.

The design intentionally favors:

- Clear static pages over heavy frameworks
- Personal visual language over generic portfolio templates
- Simple interactions over complex animations
- A handcrafted feeling over overly polished presentation
- Experimentation, imperfection, and individuality

## Project Structure

```text
.
├── index.html                 # Main website entry point
├── style.css                  # Global styles for layout, typography, and visual design
├── README.md                  # Project documentation
├── assets/
│   ├── images/                # Profile, collage, and project images
│   └── PDF/                   # Resume and other PDF files
└── projects/                  # Individual project detail pages
```

Key files:

- `index.html` contains the main page structure, navigation, content sections, and Google Analytics 4 tag.
- `style.css` contains the site-wide visual styling and responsive behavior.
- `projects/` contains standalone pages for selected portfolio projects.
- `assets/` stores images, PDFs, and other static files used by the site.

## Local Setup

This is a static website with minimal dependencies. You do not need Node.js, a package manager, or a build step to run it.

To view the website locally, clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/iamdanbi/iamdanbi.github.io.git
cd iamdanbi.github.io
```

Then either open `index.html` directly, or run a simple local server:

```bash
python3 -m http.server 8000
```

Visit:

```text
http://localhost:8000
```

Using a local server is recommended if you want browser behavior that more closely matches deployment on GitHub Pages.

## Deployment

The site is designed to be hosted with GitHub Pages. Since this is a static website, deployment only requires pushing the HTML, CSS, and asset files to the repository branch configured for GitHub Pages.

No build command is required.

## Reuse and Learning

You are welcome to use, modify, and learn from this project. Feel free to copy parts of the structure, styling, or implementation for your own personal website or portfolio.

If you adapt the code, I would appreciate attribution, especially if you reuse larger portions of the design or source structure.

## License

This project is released under the MIT License.

You are free to copy, modify, adapt, and reuse the code with attribution. The website content, personal writing, images, resume, and biographical information are personal materials, so please do not present them as your own.
