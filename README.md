# MyorkSlydes

**MyorkSlydes** is an open-source, browser-based presentation editor prototype from Two Plasma Studios. It is the slide-focused companion to MyorkText, with a long-term goal of supporting common presentation formats and multilingual code-rich slides.

## Current features

- Turkish and English interface
- Create, delete and navigate slides
- Rich text formatting, colors, alignment, images, shapes, tables and basic charts
- Code blocks with language labels for HTML, JavaScript, TypeScript, Python, CSS, Java, Dart, React/JSX, JSON, SQL, C++, C#, Go, Rust, Kotlin and Swift
- Local draft autosave and recovery
- Import MyorkSlydes JSON / `.myorksldy` files
- Save to the versioned MyorkSlydes JSON format
- Export to HTML, PDF, PNG/JPEG slide images and PPTX
- Arrow-key navigation in presentation mode

## Run

Open `program/myorkslydes.html` in a modern desktop browser. PDF, image and PPTX exports use browser-loaded libraries, so those features require an internet connection unless dependencies are bundled locally.

## Current limitations

- **Prototype:** not yet a complete replacement for Microsoft PowerPoint or LibreOffice Impress.
- PPTX export currently prioritizes readable text and embedded raster images; complex formatting, native editable shapes, chart data, animations, speaker notes and transitions are not fully preserved.
- PNG/JPEG export downloads one image per slide.
- Browser local storage is local to the current browser/profile; it is not cloud sync.
- External libraries and browsers may behave differently. Test important presentations after exporting.

## Roadmap

- Improve import/export fidelity and support more presentation formats
- Preserve layout, shapes, charts and theme information in a structured document model
- Add editable slide ordering and richer presenter controls
- Add regression tests for file import/export
- Package desktop releases after core workflows are stable

## Links

- **Studio:** https://twoplasmastudios.github.io/
- **All projects:** https://twoplasmastudios.github.io/projects.html
- **Source:** https://github.com/TwoPlasmaStudios/myorkslydes

---

Made by **Two Plasma Studios**.
