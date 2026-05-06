Alpabeto — Project Overview

Purpose
- Child-friendly alphabet tracing web app used for a CBAR project.

Kept (active)
- `index.html`, `next.html`, `trace.html`, `about.html`
- `script.js`, `style.css`
- design pages: `design4/design4.html`, `sandbl/design2.html`, `titik/design1.html`, `tunog/design3.html`
- Media files used by the app live in `titik/` and `tunog/` (audio `.mp3` and images `.png`).

Archived (older/duplicate files)
- `archive/` contains older versions and duplicate media (e.g., `tracev1.html`, `design2v1.html`, duplicate `*(1).mp3` and `*(1).png` files).

Notes
- I removed the floating interactive guide from the main pages and archived older tracing versions.
- Duplicate media from `tunog/` were moved to `archive/tunog/`.

How to preview locally
- From the project root run a simple HTTP server and open `index.html` in your browser:

```bash
python -m http.server 8000
# then open http://localhost:8000/index.html
```

Suggested next steps
- Consolidate shared media into a single `media/` folder and update HTML paths (optional).
- Remove any remaining files you no longer need after reviewing `archive/`.

If you want, I can consolidate media now or further tidy `design*` files.
