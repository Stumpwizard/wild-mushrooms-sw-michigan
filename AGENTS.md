# Publication target — user requirement

The fixed production URL for this guide is:
https://stumpwizard.github.io/wild-mushrooms-sw-michigan/

The user directed on September 27, 2026 that the latest version and all future updates use this URL.

- Treat `Stumpwizard/wild-mushrooms-sw-michigan` on GitHub as the authoritative repository.
- Publish every requested update to this repository's `main` branch. GitHub Pages publishes from `main` at `/(root)`; preserve `.nojekyll`.
- Edit the root `index.html` and any supporting `data/` files. This site requires no build step.
- Keep the exact production URL and canonical link. Do not rename or move the repository, configure a different domain, or switch hosting unless the user explicitly changes this requirement.
- Do not publish future versions to the former ChatGPT Sites URL. Its older source checkout is superseded by this repository.
- Preserve the first-visit safety acknowledgement, accessibility behavior, mobile search, species data, medicinal evidence notes, and field guidance when making unrelated changes.
- Before updating `main`, check for newer upstream commits and preserve other edits. Never force-push over upstream work.
- Verify that the GitHub Pages build/deployment for the new commit succeeds. Return the fixed URL above; do not claim publication if deployment failed.
