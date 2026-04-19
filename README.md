# Mohamed Tahiri — Personal Portfolio

> A clean, fully responsive personal portfolio website built with HTML, CSS, and vanilla JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-All%20Devices-4CAF50?style=flat)

---

## Live Preview

🔗 [View Portfolio](https://github.com/tahiri-devv) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/mohamed-tahiri-mt2026)

---

## Overview

This is my personal developer portfolio showcasing my skills, services, and projects as a future software engineer. It is designed to be fast, accessible, and visually sharp on any screen size — from small phones to large desktops.

---

## Features

- **Fully responsive** — optimized for mobile (320px+), tablet, desktop, and large screens (1400px+)
- **Mobile hamburger menu** — smooth animated navigation for small screens
- **Hero section** with animated entrance effects and stats bar
- **Services section** highlighting core technical offerings
- **Projects section** with card-based layout and GitHub links
- **Contact section** with a functional form via Formspree
- **Smooth scroll** with fixed-header offset correction (`scroll-padding-top`)
- **CSS animations** — staggered fade-up and slide-in effects on page load
- **No frameworks, no dependencies** — pure HTML, CSS, JS

---

## Project Structure

```
portfolio/
├── index.html            # Main HTML file
├── styleportfolio.css    # All styles + responsive breakpoints
├── backround.jpg         # Hero background image
├── pythonproject.avif    # Project thumbnail — Web Scraping
└── cproject.png          # Project thumbnail — Student Management
```

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Introduction, title, CTA button, social links, and stats |
| **Services** | Front-End Development, Web Scraping, API Integration |
| **Projects** | Web Scraping Books (Python), Student Management System (C) |
| **Contact** | Email form via Formspree + direct contact links |
| **Footer** | Copyright and social media links |

---

## Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| `min-width: 1400px` | Large screens — wider paddings |
| `max-width: 1024px` | Tablets — reduced paddings |
| `max-width: 768px` | Mobile — stacked layout, hamburger menu |
| `max-width: 420px` | Small phones — full-width buttons, compact stats |

---

## Setup & Usage

No build step required. Simply open `index.html` in a browser.

```bash
git clone https://github.com/tahiri-devv/portfolio
cd portfolio
open index.html
```

To deploy, upload all files to any static hosting service (GitHub Pages, Netlify, Vercel).

---

## Contact Form Setup

The contact form uses [Formspree](https://formspree.io/). To activate it:

1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form and copy your form ID
3. In `index.html`, replace `TON_ID` in the form action URL:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic structure |
| CSS3 | Styling, animations, responsive layout |
| JavaScript (Vanilla) | Hamburger menu toggle |
| Google Fonts | Syne (headings), Playfair Display (italic sub) |
| Font Awesome 6 | Icons |
| Formspree | Contact form backend |

---

## Projects Featured

### Web Scraping Books — Python
A web scraper built with Python that extracts book data (title, price, rating) from [books.toscrape.com](http://books.toscrape.com) and exports it to CSV.

🔗 [View on GitHub](https://github.com/tahiri-devv/web-scraping-books)

---

### Student Management System — C
A terminal-based student management application written in C. Supports adding, searching, updating, and deleting student records using file storage.

🔗 [View on GitHub](https://github.com/tahiri-devv/Student-Management-System-in-C)

---

## Author

**Mohamed Tahiri**
Future Software Engineer — Python · Web · Git

- GitHub: [@tahiri-devv](https://github.com/tahiri-devv)
- LinkedIn: [mohamed-tahiri-mt2026](https://www.linkedin.com/in/mohamed-tahiri-mt2026)
- Email: mtahiri2030@gmail.com

---

## License

This project is open source and available under the [MIT License](LICENSE).
