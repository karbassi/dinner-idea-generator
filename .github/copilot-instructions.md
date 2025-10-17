# Copilot Instructions - Dinner Idea Generator

## Project Overview
Single-page HTML application with embedded CSS. No build system, framework, or external dependencies - pure vanilla HTML/CSS/JS intended for direct browser usage.

## Architecture
- **`index.html`**: Self-contained landing page with embedded styles
- Pure static HTML - can be opened directly in browser or served via any static host
- No JavaScript functionality yet (currently static content only)

## Design System
- **Color Palette**: Pastel gradient background (light pink to light cyan)
- **Typography**: System font stack (`-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto...`)
- **Layout**: Centered card design with shadow and rounded corners (20px border-radius)
- **Responsive**: Mobile breakpoint at 600px - reduces padding and font sizes

## Development Workflow
- **No build step**: Edit `index.html` and refresh browser
- **Testing**: Open `index.html` directly in browser or use local server like `python -m http.server`
- **Deployment**: Static hosting (GitHub Pages, Netlify, Vercel, etc.)

## Coding Conventions
- **Inline styles**: All CSS embedded in `<style>` tag in `<head>`
- **No frameworks**: Keep vanilla - avoid suggesting React/Vue/etc unless explicitly requested
- **Self-contained**: All code in single file for simplicity
- **CSS reset**: Universal selector (`*`) sets margin/padding to 0 and box-sizing to border-box

## Future Development Patterns
When adding interactivity:
- Embed `<script>` tags at end of `<body>` for vanilla JavaScript
- Maintain self-contained single-file approach unless project evolves to need modularity
- Keep the gradient aesthetic and centered card layout consistent
- Use semantic HTML and maintain accessibility (ARIA labels, semantic tags)

## Key Files
- `index.html` - Entire application (HTML + CSS, future JS)
- `README.md` - Project name only (minimal documentation)
