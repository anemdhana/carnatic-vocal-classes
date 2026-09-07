# Carnatic Vocal Classes

This small static site is designed for GitHub Pages. It includes:

- Top navigation with a hover-drop menu (Sarali Swaras → Sarali-1/2/3)
- Breadcrumb that updates when you select an item from the drop menu
- Two-column layout: left pane (tabs: Sarali 1, Song) and right pane (tabs: Images, Audios)
- Smooth animations and a pleasant serif/sans font pairing (Merriweather + Inter)

How to use / deploy

1. The site is in the repository root. To preview on GitHub Pages, push to `main` and enable Pages to serve from the repository root or the `main` branch.

2. Replace placeholders:
   - assets/images/sarali1-sheet.svg — replace with the sheet image you attached (rename to this path)
   - assets/audio/sarali1.ogg or assets/audio/sarali1.mp3 — place your provided audio file(s) in `assets/audio/` and ensure names match (e.g. `sarali1.ogg` or `sarali1.mp3` depending on selection mapping).

3. The menu JS maps selection `data-path="sarali-1"` to `assets/images/sarali-1-sheet.svg` and `assets/audio/sarali-1.(ogg|mp3)`. Upload your real files with those names for the page to show content.

Want me to:
- Commit the real image/audio if you upload them here, or
- Scaffold Sarali-2/3 pages?