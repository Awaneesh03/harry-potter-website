# Harry Potter Website

A cinematic single-page Harry Potter fan website built with plain HTML, CSS, and a small amount of JavaScript.

The site presents the seven-book series with a more polished visual style, smoother animations, and a stronger browsing experience across desktop and mobile.

## Preview

This project includes:

- A full-screen hero section with layered visual effects
- A responsive book gallery covering all seven Harry Potter books
- Dedicated sections for Hogwarts houses and magical highlights
- Scroll-reveal animations and an adaptive sticky header
- Reduced-motion support for better accessibility

## Tech Stack

- `HTML5`
- `CSS3`
- Vanilla `JavaScript`
- Google Fonts: `Cinzel` and `Cormorant Garamond`

## Project Structure

```text
.
├── index.html
├── style.css
├── book1.jpg
├── book2.jpg
├── book3.jpg
├── book4.jpg
├── book5.jpg
├── book6.jpg
└── book7.jpg
```

## Run Locally

Since this is a static website, no build step is required.

1. Clone the repository:

```bash
git clone https://github.com/Awaneesh03/harry-potter-website.git
```

2. Open the project folder:

```bash
cd harry-potter-website
```

3. Launch `index.html` in your browser.

If you want a local development server, you can use:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Features

### Improved User Experience

- Cleaner content hierarchy with distinct sections
- Better navigation with anchor links
- More readable spacing and typography
- Responsive layout for tablets and phones

### Animation and Visual Design

- Scroll-based reveal effects
- Hover elevation for interactive cards
- Ambient background glow and layered gradients
- Sticky header that changes state on scroll

### Accessibility Considerations

- Semantic sectioning and navigation labels
- Descriptive image alt text
- Reduced-motion support via `prefers-reduced-motion`

## Customization

You can easily personalize the site by editing:

- [index.html](/Users/awaneeshgupta/Documents/GitHub/harry-potter-website/index.html:1) for content and section structure
- [style.css](/Users/awaneeshgupta/Documents/GitHub/harry-potter-website/style.css:1) for colors, spacing, typography, and animation

Useful places to update:

- Hero text and call-to-action buttons
- Book descriptions
- House section copy
- Color variables in `:root`

## Deployment

This project can be deployed on any static hosting platform, including:

- GitHub Pages
- Netlify
- Vercel
- Azure Static Web Apps

## Notes

This is a fan-made website created for learning and portfolio purposes.

The Harry Potter name, characters, and related world elements belong to their respective copyright and trademark owners.
