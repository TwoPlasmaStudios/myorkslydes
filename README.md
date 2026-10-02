# MyorkSlydes

**MyorkSlydes** is a browser-based presentation editor prototype by Two Plasma Studios. The current implementation is a single HTML file with a slide list, editing toolbar and presentation mode.

> **Project status:** Prototype / work in progress. Not every presentation feature is production-ready, and browser editing behavior may vary.

## Current features

- Turkish and English interface toggle
- Create and delete slides
- Navigate between slides and select them from a slide panel
- Edit slide content in the browser
- Save slide data using the browser's file download flow
- Text formatting and alignment controls
- Insert an image using an image URL
- Insert a table by specifying rows and columns
- Basic rectangle, circle and line insertion
- Basic bar chart insertion
- Simple timed presentation mode

## Run it

1. Clone or download this repository.
2. Open `program/myorkslydes.html` in a current desktop browser.
3. Create slides and use the toolbar to edit or present.

No package installation or build step is required for the current HTML prototype.

## Known limitations

- The project uses browser editing APIs such as `document.execCommand`; formatting can vary by browser.
- Presentation mode currently advances automatically on a timer and has limited controls.
- Shapes and charts are basic visual elements, not a full vector or chart-editing system.
- The current save/export behavior should be tested with real presentations before relying on it for important work.
- There is no cloud collaboration or account system.

## Roadmap

- Reliable project format with import/export
- Reorder slides and add keyboard navigation
- Better presenter controls and transitions
- Editable chart data and shape properties
- Autosave and recovery
- Browser-based regression tests

## Links

- **Studio website:** https://twoplasmastudios.github.io/
- **All studio projects:** https://twoplasmastudios.github.io/projects.html
- **Source code:** https://github.com/TwoPlasmaStudios/myorkslydes

---

Made by **Two Plasma Studios**.
