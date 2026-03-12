# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for the "Beyond APIs: Collecting Web Data for Research using the National Internet Observatory" tutorial at ICWSM 2025. It's a single-page responsive website built with vanilla HTML, CSS, and JavaScript.

- **Live Site**: https://national-internet-observatory.github.io/beyondapi_icwsm25
- **Repository**: National-Internet-Observatory/beyondapi_icwsm25
- **Deployment**: GitHub Pages from main branch

## Development Commands

This is a static website with no build process. For local development:

```bash
# Serve locally (Python 3)
python -m http.server 8000

# Or simply open the HTML file directly
open index.html
```

## Architecture

### File Structure
- `index.html` - Main single-page website
- `styles.css` - All CSS styling with responsive design
- `script.js` - JavaScript for smooth scrolling navigation
- `optimized_photos/` - Compressed organizer headshots for web
- `photos/` - Original high-resolution photos

### Key Technical Details
- **Responsive Design**: Mobile-first approach with flexbox layouts
- **Navigation**: Sticky navbar with smooth scrolling to sections
- **Sections**: Overview, Tutorial Details, Organizers
- **Icons**: Font Awesome via CDN
- **Images**: Optimized versions in separate directory

## Commit Conventions

Follow the existing pattern using emoji prefixes and conventional commit format:
- 🎉 feat: New features
- 🔄 refactor: Code refactoring  
- 🎨 style: UI/styling changes
- 📝 docs: Documentation updates

## Content Management

When updating organizer information or content:
- Organizer details are in the "Organizers" section of `index.html`
- Photos should be optimized and placed in `optimized_photos/`
- Maintain consistent styling and responsive behavior
- Test on both desktop and mobile viewports