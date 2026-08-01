# personal-portfolio

A responsive, multi-page personal portfolio website built with semantic HTML5 and pure CSS (no frameworks, no build tools). Created as part of the [roadmap.sh frontend projects](https://roadmap.sh/projects/portfolio-website) track — first as a structure-only HTML project, then upgraded with CSS for styling and responsiveness.

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero intro, Projects list, Work Experience, Education, and teacher reviews |
| Projects | `projects.html` | Full write-ups of each project |
| Articles | `articles.html` | Curated list of articles/resources on frontend development |
| Contact | `contact.html` | Contact form (name, email, subject, message) |

All four pages share the same header, navigation, and footer, and are linked together via a consistent nav bar.

## Features

- **Semantic HTML** — `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `blockquote`, `time`, used according to meaning rather than appearance
- **Responsive layout** — built with Flexbox; the homepage's 3-column layout collapses to a single column under 860px, and the header/nav stacks and centers under 600px
- **SEO meta tags** — title, description, keywords, author, and Open Graph tags on every page
- **Accessible forms** — every input has an associated `<label>`, required fields are marked, and focus states are visible
- **External link safety** — all `target="_blank"` links include `rel="noopener noreferrer"`
- **Dark mode** — automatically follows the visitor's OS-level `prefers-color-scheme` setting via CSS custom properties, no toggle/JS needed
- **Google Fonts** — [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) for headings, [Inter](https://fonts.google.com/specimen/Inter) for body text, [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) for nav links and labels

## Tech Stack

- HTML5
- CSS3 (custom properties, Flexbox, media queries — no CSS framework)
- Google Fonts (loaded via CDN)

## [Live Demo](https://naprikot.github.io/personal-portfolio/contact.html)
