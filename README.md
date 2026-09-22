# Vitor Santos — IT & ServiceNow Trainee Portfolio

A personal CV and portfolio website built as an academic web development project, demonstrating **semantic HTML5** and **CSS3** fundamentals — built entirely from scratch, with **no JavaScript, no CSS frameworks, and no external libraries**.

## About

This site is my personal CV, showcasing my transition from a background in translation and multilingual communication into Information Technology, with a current focus on ServiceNow platform training and web development fundamentals.

## Tech stack

- **HTML5** — semantic elements throughout (`<header>`, `<main>`, `<aside>`, `<footer>`, `<section>`, proper heading hierarchy)
- **CSS3** — including CSS custom properties (variables), CSS Grid, and Flexbox
- **Google Fonts** — Inter, loaded via `<link>`
- No JavaScript, no build tools, no dependencies

## Layout techniques

| Technique          | Used for                                                                                                                            |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------------- |
| **CSS Grid** | Page-level 2-column layout (sidebar + main content), the Technical Skills grid, the Projects grid, and the About Me highlight cards |
| **Flexbox**  | Navigation bar, sidebar internals (profile block, contact list, languages list), section headers, card internals, and the footer    |

Grid is used specifically where a genuine multi-column layout is needed; everything else — rows, columns, centering, spacing — is handled with Flexbox.

## Features

- Fully responsive layout with breakpoints at 768px, and 480px
- Sticky navigation header with anchor links to each section
- Highlighted "current" entries in Education and Experience, visually distinguished from past entries
- Color-coded project category badges (Academic / Training / Personal)
- Accessible focus states (`:focus-visible`) for keyboard navigation
- Minimum 44px tap targets on mobile interactive elements
- No layout-breaking dependency on JavaScript — the entire site works with CSS alone

## Sections

1. **About Me** — introduction and current focus
2. **Education & Training** — academic and vocational background, including current ServiceNow training
3. **Technical Skills** — technologies studied or in progress
4. **Experience & Professional Development** — work history and current training role
5. **Projects & Learning** — academic, training, and personal projects
6. **Languages** — spoken languages and proficiency levels
7. **Contact** — email, LinkedIn, GitHub, and location

## File structure

```
├── index.html
├── style.css
├── photo.jpg
├── icon-email.svg
├── icon-linkedin.svg
├── icon-github.svg
├── icon-location.svg
```

## Running locally

No build step required. Clone or download the project, then open `index.html` directly in a browser — or serve the folder with any static file server (e.g. the VS Code "Live Server" extension) for the closest match to a real hosting environment.

## Design credits

Initial visual direction explored with Google Stitch; all HTML and CSS implementation was hand-built and debugged from that starting point.

## Author

**Vitor Santos**
[linkedin.com/in/vitor-b-santos](https://linkedin.com/in/vitor-b-santos) · [github.com/VitorBSantosD](https://github.com/VitorBSantosDev)
