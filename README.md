# Beds-darts-tournament
a program to help create darts tournaments

## Running it
Single self-contained `index.html` (React + Babel + Tailwind loaded from CDN, no build step). Deploy as-is to Netlify - no build command needed, `netlify.toml` sets the publish directory to the repo root.

Real-time sync uses a Firebase project (config is inline in `index.html`). Access control is just a 4-digit room PIN, so make sure your Firestore security rules restrict writes appropriately rather than relying on the PIN alone.
