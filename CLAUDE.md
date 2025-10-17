# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static wedding invitation website (faire-part de mariage) built with vanilla HTML and CSS. The project is designed to be simple, elegant, and ready for deployment on static hosting platforms.

## Development

### Preview the site
Open `index.html` directly in a web browser:
```bash
# Linux
xdg-open index.html

# macOS
open index.html

# Or use a simple HTTP server
python3 -m http.server 8000
```

### Content Customization
All user-facing content is in `index.html`:
- **Lines 19-20**: Couple names
- **Lines 24-41**: Event details (date, time, location, reception)
- **Lines 44-50**: RSVP information and contact details
- **Line 56**: Footer message

### Styling
The site uses a single CSS file (`css/style.css`) with:
- Gold accent color: `#d4af37` (used for ornaments, names, borders)
- Serif font stack: Georgia, Times New Roman
- Responsive design with breakpoint at 768px
- Centered layout with gradient background

## Architecture

The site follows a simple single-page structure:
- `index.html`: Main page with semantic HTML sections (header, couple, details, rsvp, footer)
- `css/style.css`: All styling including mobile responsiveness
- `images/`: Directory for wedding photos or decorative images (currently empty)

## Deployment

The site is static HTML and can be deployed to:
- **GitHub Pages**: Enable in repository Settings → Pages → Deploy from main branch
- **Netlify**: Drag and drop the project folder
- **Vercel**: Connect the GitHub repository

No build process is required.
