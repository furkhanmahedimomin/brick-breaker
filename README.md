# 🧱 Brick Breaker

A classic Breakout/Brick Breaker game built with plain HTML5 Canvas, CSS, and JavaScript — no frameworks, no build step, no dependencies.

## Play
- **Move paddle:** ← / → arrow keys, A/D keys, mouse move, or touch drag
- **Launch ball:** Space bar or click
- Clear all bricks to advance to the next (faster) level
- You have 3 lives — game ends when they run out

## Deploy to GitHub Pages

1. Create a new repository on GitHub, e.g. `brick-breaker`
2. Push these files (`index.html`, `README.md`) to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Brick Breaker game"
   git branch -M main
   git remote add origin https://github.com/<your-username>/brick-breaker.git
   git push -u origin main
   ```
3. On GitHub, go to your repo → **Settings** → **Pages**
4. Under "Build and deployment" → Source: **Deploy from a branch**
5. Branch: `main`, folder: `/ (root)` → **Save**
6. Wait ~1 minute, then visit:
   `https://<your-username>.github.io/brick-breaker/`

That's it — single static file, zero build config needed.
