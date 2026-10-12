# Cellstrike AI — Battery Health Intelligence

A responsive front-end prototype inspired by the visible Cellstrike AI / EV Battery Health dashboard.

## Run locally
1. Download and unzip this project.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. No installation or paid account is needed.

## Features
- Dark EV battery dashboard and responsive sidebar navigation
- Adjustable battery parameters and illustrative SOH estimate
- Pack health visual with 96 simulated cells
- Explainability contribution bars
- Battery life passport summary download and print-to-PDF
- Local CSV preview (files are not sent to a server)
- Responsive layout for laptop and mobile

## Important limitations
This is a **demonstration prototype**, not the original Emergent source code. It does not connect to a vehicle, BMS, server, or validated machine-learning model. The battery-health calculation and confidence/feature values are illustrative only. Do not use them for safety-critical or real battery decisions. A production system would need validated data, model evaluation, cybersecurity, and professional battery diagnostics.

## GitHub Pages (free hosting)
1. Create/sign in to GitHub.
2. Create a new **public** repository, e.g. `cellstrike-ai-battery-health`.
3. Upload `index.html`, `style.css`, `app.js`, and `README.md` to the repository root.
4. Open repository **Settings → Pages**.
5. Under Build and deployment, select **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then Save.
7. Wait for the published URL shown in Settings → Pages.

The Google Fonts import is optional; if unavailable, the page falls back to system fonts.
