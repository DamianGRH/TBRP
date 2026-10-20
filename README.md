# Leonida Network — GitHub Pages starter

Open index.html directly to try the prototype. No installation, API key, build, or external dependencies are required.

## Publish on GitHub Pages
1. Create a GitHub repository and upload index.html to its root.
2. Open repository Settings → Pages.
3. Select Deploy from a branch, select main and /(root), then Save.
4. GitHub displays your Pages address when deployment finishes.

## Included
- Responsive dark and pink community hub inspired by the supplied reference.
- Searchable and filterable content library with detail dialogs.
- Illustrative SVG map with zoom, pointer panning, category filters, location search, keyboard-selectable markers, and discoveries saved in localStorage.
- No fabricated game news, mission details, vehicle statistics, or real map coordinates.

## Before a public launch
Replace the community setup dialog with your actual Discord link. Add verified articles, publication dates, source links, vehicle entries, and spoiler-aware mission guides. Replace the concept SVG map and fictional demonstration coordinates with properly licensed, verified map data. Supply original or licensed artwork; the current artwork is a decorative SVG skyline, not GTA VI imagery.

The map is a functional UI prototype, not a complete GTA VI map. News and library cards are editorial placeholders. Browser progress is local to each browser/device; private mode or clearing storage can remove it. No accounts, submissions, live updates, or cross-device sync are connected. Those need a separate backend, such as Supabase or Firebase, or a publishing workflow such as GitHub Actions.

## Editing
The single index.html contains styles, markup, and JavaScript. Edit the news and library arrays for content; edit points and types for demonstration markers. Content is inserted using textContent. For a growing catalogue, move these arrays into JSON files and serve the site through HTTP.

## Verification
JavaScript syntax and HTML structure checked locally. Browser visual and interaction QA still required before production.

## CG Scripts inspired scrolling update
Full-height gradient hero, native smooth anchor scrolling, pinned opening-curtain reveal, scroll progress bar, moving announcement band, section entrance effects, card hover lifts, active navigation, and back-to-top control. The motion button pauses effects and remembers the choice; system reduced-motion preferences disable them automatically. No wheel hijacking or scroll-blocking library.
