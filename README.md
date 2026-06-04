# Country Guessr

A Worldle-style country-guessing game. Pick a continent, the page shades a random country on an unlabeled map, and you have 6 guesses with **hot / warm / cool / cold / borders** feedback.

Single static `index.html` — no build step. Hosted on private GitHub Pages (Gusto org members only).

## Data sources

- World map: [`world-atlas`](https://github.com/topojson/world-atlas) (TopoJSON, via jsDelivr CDN)
- Country metadata: [REST Countries](https://restcountries.com) (region, centroid, borders)

Both fetched at runtime from the browser.
