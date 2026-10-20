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

Boundaries from the LA Times [Mapping L.A.](https://maps.latimes.com/neighborhoods/) project (v6 neighborhood set, Orange County entries removed). Basemap tiles by Esri and OpenStreetMap.

Neighborhood statistics come from the U.S. Census Bureau's American Community Survey 2020–2024 5-year estimates (via the [Census Reporter](https://censusreporter.org) API). Neighborhoods are not census geographies, so each block group is assigned to the neighborhood containing its centroid; counts are summed and medians (income, age, rent, home value) are household-weighted averages of block-group medians. Foreign-born share uses tract-level data the same way. Treat the figures as close approximations. Descriptions are Wikipedia summaries where available.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. A single `index.html` plus `neighborhoods.json`; no build step.
