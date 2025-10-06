# Minimal Birthday Surprise (Mobile, No-Scroll, Multi-Page)

This project has **two pages**:
- `index.html` — Public site with 2 full-screen pages (no scroll):
  1) Typewriter intro: `From Phukao` line break `To Nawaa`
  2) Gallery: swipe left/right, per-image captions, smooth motion
- `admin.html` — "หลังบ้าน" config UI to add/edit images + captions and general text.
  Data is saved in `localStorage` under key `hb_config` (no backend).

## Quick Start (VS Code on Mac)
1. Open this folder in VS Code.
2. Install the "Live Server" extension.
3. Open `admin.html` with Live Server. Add images & captions, save.
4. Open `index.html` with Live Server to view the site.

## Notes
- The gallery is portrait-oriented, centered with rounded corners and a margin from the edges.
- Images are scaled to fit within a phone-like 9:16 frame. Use vertical photos for best results.
- Config can be exported/imported as JSON from the Admin page.
- If no images are set yet, the site shows placeholders and a hint to open the admin.
