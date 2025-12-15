# Bangladesh 2.0 Project Instructions

## Project Overview
This is a static HTML/CSS website for "Bangladesh 2.0", showcasing ideas, innovation, vision, and challenges in New Bangladesh. The site consists of a single page with header, main, and footer sections.

## Architecture
- **Structure**: Single `index.html` file linked to `style.css`.
- **Assets**: Images stored in `assets/` folder (e.g., hero.png, social icons).
- **No JavaScript**: Pure static site, no dynamic functionality.
- **Fonts**: Fira Sans loaded from Google Fonts.

## Key Components
- **Header**: Navigation bar with title and sign-in button, plus hero banner with title, description, and image.
- **Main**: Currently empty, intended for content sections.
- **Footer**: Placeholder for footer content.

## Styling Conventions
- **Primary Color**: `#006A50` (green) for buttons and accents.
- **Text Color**: `#0E0E0E` (black) for primary text.
- **Font**: Fira Sans, applied via `.fira-sans-bold` class.
- **Buttons**: Use `.primary-button` class for green, rounded buttons (e.g., `<button class="primary-button">Explore</button>`).
- **Text Styling**: Use `.primary-text` for bold, dark text (e.g., `<h3 class="primary-text">Title</h3>`).
- **Layout**: Flexbox for horizontal alignments (nav, banner). Margins: 60px left/right for main content areas.
- **Banner**: Background `#C6E4D6`, rounded corners (24px), centered content.

## Developer Workflows
- **Editing**: Modify `index.html` for structure, `style.css` for styles.
- **Preview**: Open `index.html` directly in browser; no build step required.
- **Assets**: Place images in `assets/` and reference as `src="assets/filename.png"`.
- **Responsive**: Add media queries in `style.css` for mobile/desktop adjustments.

## Patterns and Examples
- **Adding Sections**: Insert content in `<main>` with classes like `.overveiw-container` for card layouts.
- **Cards**: Use `.overveiw-cards` (flex) and `.overveiw-card` (background #F5F5F5, rounded 16px, padding 24px).
- **Navigation**: List items in `<ul>` with button styles for links.
- **Image Usage**: Hero image in banner: `<img src="assets/hero.png" alt="Hero">`.

## Notes
- Ensure image paths are relative to root (e.g., `assets/hero.png`).
- Expand main content using existing card styles for consistency.</content>
<parameter name="filePath">d:\PERSONAL\WEB_DEVELOPMENT\PROJECTS\Bangladesh 2.0\.github\copilot-instructions.md