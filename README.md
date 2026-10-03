# Wild Mushrooms of SW Michigan

A seasonal mushroom field guide for southwest Michigan, with example photos, common names, identification characteristics, lookalikes, and clearly marked edibility information.

## Fixed publishing address

**https://stumpwizard.github.io/wild-mushrooms-sw-michigan/**

This is the production address for the latest guide and all future updates, as requested on September 27, 2026. This repository is the authoritative source. Keep the repository name and Pages address unchanged unless the owner explicitly requests a change.

GitHub Pages publishes automatically from **main → /(root)**. The `.nojekyll` file publishes the static HTML directly. Update the root `index.html` and supporting `data/` files on `main`, then confirm the Pages deployment succeeds. The former ChatGPT Sites copy is no longer the publication target.

## How it works

- Application code and styles are in `index.html`, with the reference-photo catalog in `data/photo-galleries.js`; no build step or server is required.
- The guide contains 79 mushrooms and species groups, local occurrence references, medicinal-use evidence notes, and spore-print, foraging, handling and cooking guidance.
- Reference galleries contain four credited iNaturalist photos for each of 77 entries (308 photos), with touch swiping, previous/next buttons, keyboard navigation, and a current-photo counter. Images retain their full frame and load lazily. Two rare historical Pholiota entries remain explicitly without verified reference photos.
- The photo catalog records each image's source, license, attribution, taxon, and selection method (taxon gallery or Research Grade observation), checked October 3, 2026. Photo credits and source links follow the selected slide. Group examples are labeled; photographs are not necessarily from Michigan, and their identifications are not independent specimen verification. The site uses the saved catalog instead of making a taxon API request for every card.
- Supporting source comparisons and medicinal notes are included in `data/`. The October 2 Pholiota comparison is in `data/pholiota-checklist.json`, with 16 additional entries, exact local evidence, historical-name handling, and explicit native-status limits.
- A first-visit safety acknowledgement is remembered in the visitor’s browser when available.
- Search supports common names, scientific names, combined names, and mobile Search/Enter submission.
- A visitor’s uploaded photo stays in their browser. Visible-feature matching is a comparison tool, not automated photo identification.

## Safety

Do not eat a wild mushroom based on this guide, its edibility labels, or a photo. Verify specimens in person with a qualified expert. Seasonal windows are approximate, and this is a curated guide rather than a complete species census.
