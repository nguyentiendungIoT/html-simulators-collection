# HTML Simulators Collection (Embedded Systems / FreeRTOS / 8-bit Computer)

A curated set of interactive, **single-file HTML** simulators/visualizers that explain embedded/RTOS internals and digital logic concepts.

**Why this repo exists (HR-friendly):** it demonstrates the ability to turn low-level concepts into clear, interactive learning tools using clean UI + vanilla JavaScript.

## Quick demo
- Open [index.html](index.html) locally (double-click), or serve a local web server for best results:
  - PowerShell: `python -m http.server 8000`
  - Then open: `http://localhost:8000/`

## What’s inside
- **FreeRTOS / Cortex‑M:** scheduler, tick, PendSV, heap, lists, queues, TCB, context switching…
- **8-bit computer / Ben Eater style:** bus/clock/PC + ALU-related demos
- **EEPROM:** AT28C16 lab + programmer/simulator
- **Digital logic:** display decoder, logic labs
- **Memory:** RAM simulation + RTOS memory explorer

## Repository layout
- `freertos/` — FreeRTOS + Cortex‑M focused simulators
- `8bit/` — 8-bit computer related demos
- `eeprom/` — EEPROM/AT28C16 demos
- `logic/` — digital logic demos
- `memory/` — RAM/memory visualizers
- `database/` — MySQL proposal/simulator docs
- `cs/` — computer science visualizations
- `archive/` — duplicates/backups (kept for reference)

## Recommended: GitHub Pages (for a clean HR viewing experience)
If you enable GitHub Pages, HR can browse the demos without downloading anything:
1. Repo **Settings → Pages**
2. **Deploy from a branch**
3. Branch: `main`, Folder: `/ (root)`
4. Your homepage becomes `index.html`.

## Notes
- These are static pages (HTML/CSS/JS) and intentionally avoid build steps.
- Most pages use CDN libraries (e.g., Tailwind). An internet connection is recommended.

---

### Vietnamese summary
Bộ sưu tập mô phỏng/visualizer bằng **HTML 1-file**, tập trung vào FreeRTOS/embedded/digital logic. Có trang tổng hợp [index.html](index.html) để HR mở xem nhanh.
