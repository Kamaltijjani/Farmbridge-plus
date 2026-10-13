# FarmBridge+

A static farmer-to-buyer marketplace prototype built with HTML, CSS and JavaScript.

## Run

From this folder, run `python -m http.server 8000`, then open `http://localhost:8000`.

- `index.html`: lightweight landing page with searchable demo listings.
- `index (1).html`: alternate interactive design with combined category/search filters, testimonials and a sample Leaflet map. Linked from the main page.

No build step or package install is required. Fonts, icons, photographs and map tiles use external services; internet access is needed for those resources. The map has a fallback when Leaflet cannot load.

## Scope

All products, prices, statistics, testimonials and map locations are demonstration content. This repository has no authentication, database, checkout, messaging or order backend. Those features require implementation before real-world use. Placeholder links explain that they are not connected.

## Checks

Search by product/seller on the main page; check a no-match search. In the alternate design, combine a category with a search term, clear the search, toggle the mobile menu and switch testimonials. Confirm that contact navigation reaches the footer.
