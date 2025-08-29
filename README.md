# Niharika — You, In Bloom 🌸

A warm, single-file HTML + CSS love/portfolio page for **Chandala Niharika**.  
Includes portrait, resume download, a floating play/pause audio control (uses `rangule.mp3`), and a tidy two-column layout for content and sidebar.

---

## Project contents
Niharika_My-love_page.html # main single-file page (HTML + inline CSS + JS)
niharika.jpg # portrait used on the page
Niharika_resume.pdf # downloadable resume
rangule.mp3 # background audio file (used by page)
style.css # optional separate stylesheet (if used)
README.md # this file

---
## Features
- Beautiful responsive layout (hero, main content, sidebar).
- Floating Play/Pause music control with accessible ARIA attrs.
- Downloadable resume link.
- Timeline / memories section (example: "Our Aruku Ride").
- Simple, easy-to-customize HTML & CSS — no frameworks required.

---

## Quick preview / run locally
Open the HTML directly in a browser, or serve it with a simple local server to avoid file-loading restrictions for audio:

### Option A — open locally
Double-click `Niharika_big_love_page.html` in your file manager or open it in the browser.

### Option B — using Python (recommended)
Run from the project folder:
```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000/Niharika_big_love_page.html
