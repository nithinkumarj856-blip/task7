#task7
# Laundry Services Landing Page

A clean, responsive landing page for a laundry service business, built with plain HTML and CSS.

## Preview

A hero section featuring a navigation bar, a headline with call-to-action, and a 3D illustration — fully responsive across desktop, tablet, and mobile.

## Features

- Responsive navbar with logo, nav links, and username badge
- Hero section with heading, description, and call-to-action button
- Fully responsive layout with breakpoints for tablet (≤900px) and mobile (≤600px)
- Mobile-optimized typography and stacked layout
- No external dependencies — pure HTML/CSS

## Tech Stack

- HTML5
- CSS3 (Flexbox, media queries, `clamp()` for fluid typography)

## File Structure

```
.
├── index.html   # Page markup
└── style.css    # Styles and responsive breakpoints
```

## Getting Started

1. Clone the repository
   ```bash
   git clone <repo-url>
   cd <repo-folder>
   ```
2. Open `index.html` in your browser — no build step or server required.

## Responsive Breakpoints

| Breakpoint | Width       | Behavior                                  |
|------------|-------------|--------------------------------------------|
| Desktop    | > 900px     | Default two-column hero layout             |
| Tablet     | ≤ 900px     | Reduced spacing and font sizes             |
| Mobile     | ≤ 600px     | Nav links hidden, hero stacks vertically   |

## Customization

- **Colors:** Update the hex values in `style.css` (primary accent: `#08a5f5`)
- **Content:** Edit the text and links directly in `index.html`
- **Hero image:** Replace the `src` in `.hero-image img` with your own illustration

## License

Add your preferred license here (e.g., MIT).
