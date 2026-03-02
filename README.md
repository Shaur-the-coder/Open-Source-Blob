# 🫧 Open Source Blob

An interactive 2D gelatinous blob simulation built with vanilla HTML5 Canvas and JavaScript. The blob is a soft-body made of 128 spring-connected points that breathes, wobbles, and hunts nearby particles — extending pseudopods and drifting its entire body to absorb them.

## ✨ Features

- **Soft-body physics** — spring-connected control points with pressure, cohesion, and organic breathing
- **Pseudopod extension** — blob bulges toward the nearest particle and drifts to absorb it
- **Tool system** with keyboard shortcuts:
  - `Q` — **Default** — click to spawn particles, drag to move the blob
  - `A` — **Attractor** — place gravity wells that pull particles and the blob
  - `B` — **Builder** — place walls (`1`) and spikes (`2`)
  - `X` — Delete nearest placed object
  - 🔄 **Reset Blob** button to restore original size and position
- **Walls** — solid golden barriers that bounce the blob and particles
- **Spikes** — red hazards that shrink the blob and destroy particles
- **Attractors** — purple gravity wells with animated spiral visuals
- **Auto-spawning particles** drift in from screen edges
- **Touch support** for mobile devices

## 🚀 Getting Started

```bash
git clone https://github.com/Shaur-the-coder/Open-Source-Blob.git
cd Open-Source-Blob
npm install
npm start
```

Open `http://localhost:3000` in your browser.

Or just open `index.html` directly — no server needed for local use.

## 🛠 Tech Stack

- **HTML5 Canvas** for rendering
- **Vanilla JavaScript** for physics and interaction
- **Express** for serving on deployment platforms

## 🌐 Deployment

Ready for [Render](https://render.com):

| Setting | Value |
|---------|-------|
| Build Command | `npm install` |
| Start Command | `npm start` |

## 📄 License

[MIT](LICENSE) — use it, remix it, blob it.
