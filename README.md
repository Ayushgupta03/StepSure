# StepSure

Interactive patient-app prototype for StepSure, a smart insole and connected app for diabetic-foot monitoring.

## What's inside

- `index.html`: the whole app in one file (HTML, CSS and JavaScript). No build step, no backend, no API keys.

## Run locally

Open `index.html` in any modern browser.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Use these settings:
   - Framework preset: **Other**
   - Build command: leave empty
   - Output directory: leave empty
4. Click **Deploy**. Every push to `main` redeploys automatically.

If the project sits under a team, check **Settings → Deployment Protection** so the production URL is public.

## Presenting

- **Free / Advanced** toggle and **Reset** sit above the phone.
- **Simulate alert** is at the bottom of the Home screen.
- Disconnect an insole from the Insoles card to show the "Monitoring incomplete" state.
