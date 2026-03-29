# Project Guidelines

## Website

This is a static HTML/CSS personal website hosted on GitHub Pages. No frameworks, no build step.

## Structure

- `index.html`: Main about page
- `talks/`: Individual talk pages with written narratives and slide galleries
- `slides/`: Slide PNGs organized by talk
- `css/style.css`: Shared styles
- `.nojekyll`: Tells GitHub Pages to skip Jekyll processing

## Style Rules

- **No dashes.** No em dashes, en dashes, or hyphens used as separators. Use pipes (`|`) for separators in navigation and titles. Use parentheses or rewrite sentences to avoid needing dashes in prose.
- **No `&mdash;` or `&ndash;` HTML entities.**
- **Venue format:** "Event, City Year" (e.g., "KubeCon EU 2026, Amsterdam"). Keep it consistent across all pages.
- **Talk narratives:** Written in first person, as if Bogdan is telling the story to the reader. Not a summary of the presentation, but the story itself. 2 to 3 paragraphs, natural and conversational.
- **Favicon:** Uses the GitHub profile picture (`favicon.png`). Must be linked in the `<head>` of every page.
- **Sidebar:** Persistent left navigation across all pages. Keep nav links in sync when adding new talks.

## Adding a New Talk

1. Export slides as PNGs into `slides/<talk-slug>/`
2. Create `talks/<talk-slug>.html` with sidebar, narrative, and slide gallery
3. Add the talk to the sidebar nav in all HTML files
4. Add the talk to the Talks section on `index.html`
