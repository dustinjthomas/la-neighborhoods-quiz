# LA Neighborhoods — Learn & Quiz

Interactive map to learn the 270 neighborhoods of Los Angeles County (including independent cities like Santa Monica, Culver City, Beverly Hills, and West Hollywood), then quiz yourself.

## Modes

- **Learn** — hover and click neighborhoods for population, density, income, age, ethnicity and a short description; browse a searchable list; filter by region. Dots show your quiz mastery.
- **Find it** — a name is shown; click the right polygon on the map.
- **Name it** — a polygon is highlighted; pick the name from four choices.

Region filters: Core LA (default), City of LA only, Westside, or the whole county. Scores and per-neighborhood mastery are saved in your browser. Questions you miss come up more often.

## Share

**Share link** copies a URL that reproduces your mode, regions and round length. **Share score** at the end of a round copies a challenge message.

## Data

Boundaries from the LA Times [Mapping L.A.](https://maps.latimes.com/neighborhoods/) project (v6 neighborhood set). Basemap tiles by Esri and OpenStreetMap.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. A single `index.html` plus `neighborhoods.json`; no build step.
