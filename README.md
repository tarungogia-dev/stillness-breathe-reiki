# Stillness – Breathe & Reiki

A single-file, mobile-first web app with two tools:

- **Mindful breathing** – configurable inhale / hold / exhale timer (default 4-7-8) with full-screen colour phases, a soft synthesized tone per phase, and screen wake-lock.
- **Reiki healing tracker** – log up to 33 points per day, see streaks, 7-day average, a 14-day chart, and play your own "healing bells" MP3 every 3 seconds.

Data is stored in the browser (localStorage / IndexedDB). Light and dark themes follow the device setting.

## Run it

No build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Deploy

Enable **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root) to host it as a static site.
