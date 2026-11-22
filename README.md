# MySurf: Sunshine Coast Surf Check

Live surf forecast for 12 Sunshine Coast breaks, from Noosa to Caloundra:
First Point, Tea Tree, Nationals, Sunshine Beach, Coolum, Mudjimba, Alex Headland,
Point Cartwright, Wurtulla, Dicky Beach, Moffat Beach and Happy Valley.

- Hourly swell, wind, tide and weather from [Open-Meteo](https://open-meteo.com/) for three coastal zones (wind from BOM ACCESS-G where available)
- Live wave-buoy readings (Caloundra, Mooloolaba, Noosa) from the Queensland Government Coastal Data System
- Official tide predictions for Mooloolaba from Maritime Safety Queensland (falls back to a model estimate)
- 0–10 rating and plain-English conditions per spot, based on each break's swell window, offshore wind, tide preference and break type
- "Best spots" ranking for any session, OpenStreetMap view with swell and wind overlays, and a side-on breaking-wave diagram
- Refresh button, auto-refresh every 30 min, offline cache

Single static file: `index.html`, hosted with GitHub Pages.
Spots, coordinates and rating settings live in the `CONFIG` and `SPOTS` blocks at the top of the script.

Map data © OpenStreetMap contributors. Surf ratings are estimates; check the water yourself.
