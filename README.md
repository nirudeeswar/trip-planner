# Group Trip Planner

A single-file, offline-friendly trip budget and itinerary planner. Built for a
5-friend, 3-night Bengaluru trip, but every number, category and day is editable.

## Features
- Editable budget table (per person or whole group, with quantity)
- Live totals, per-person and per-day cost, and a surprise buffer percentage
- Category breakdown bars
- Editable day-by-day itinerary with one-tap idea chips
- Notes, Save button, and copy/paste backup and restore
- Mobile-friendly layout, light and dark mode
- No frameworks, no build step, no server. Data is saved in your browser (localStorage)

## Use it
Open `index.html` in any browser. That's it.

## Put it online (free)
1. Push this folder to a public GitHub repository.
2. Go to Settings, then Pages, choose the `main` branch and the root folder, and save.
3. Your site will be at `https://<username>.github.io/<repo>/`.

## Customize
- Default budget items and itinerary: edit the `defaults()` function in `index.html`.
- Ideas shown under each day: edit the `IDEAS` array.
- Categories: edit the `CATS` array.
- Colors: edit the CSS variables at the top of the `<style>` block.

## Limitations
Each person's edits are stored only in their own browser. There are no accounts and no
shared live editing. Use the backup text to move a plan between devices.

## License
MIT. See `LICENSE`. Replace "Your Name" in the license with your own name.
