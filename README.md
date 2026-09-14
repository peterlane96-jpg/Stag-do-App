# William's Stag Do

A single-page interactive itinerary site for William's stag weekend in York, 2–4 April 2027. Built to be sent straight to the group — day-by-day schedule, accommodation details, a live countdown, and a packing checklist.

## Editing the plan

Everything lives in `index.html`. The TBC items (golf course, Saturday's activity, the restaurant, the bars) are marked with a red `TBC` pill — search for `pill tbc` to find and update them as they get confirmed.

## Viewing it

Open `index.html` directly in a browser, or serve the folder with any static file host.

## Publishing it

The simplest way to share a live link is GitHub Pages:

1. Push this repo to GitHub (already done if you're reading this from there).
2. In the repo settings, go to **Pages** and set the source to the `main` branch, root folder.
3. GitHub will publish it at `https://<your-username>.github.io/<repo-name>/`.

Any other static host (Netlify, Vercel, Cloudflare Pages) works the same way — just point it at this folder.
