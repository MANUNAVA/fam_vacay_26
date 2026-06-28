RIVIERA MAYA ITINERARY — DEPLOY TO NETLIFY
==========================================

This folder is ready to publish. It contains index.html (your app).

LIVE DATA
- Weather (7-day forecast) and the USD->MXN exchange rate fetch live
  every time the page loads, from free keyless APIs (Open-Meteo + ER-API).
- No API key, no account, no backend needed.
- Sargassum, dining hours, and flight status are one-tap live links.
- Your edits in the Flights tab (times/seats/gate/confirmation) save to
  the device you typed them on.

DEPLOY (drag & drop, ~30 seconds)
1. Go to app.netlify.com/drop  (no login required to try)
2. Drag THIS WHOLE FOLDER (riviera-site) onto the page
3. It goes live at a random URL like fun-name-123.netlify.app
4. (Optional) Sign in to keep it + rename the site in Site settings

UPDATING LATER
- Re-drag the folder anytime to publish changes.
- Live weather/rate refresh on their own — nothing to maintain.

NOTE
- Live fetching needs internet and won't run inside a preview sandbox.
  It works normally once deployed or opened in a regular browser.
