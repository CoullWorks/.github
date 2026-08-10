# .github

Organisation defaults + the COULLWORKS profile for GitHub.

- `profile/README.md` renders on the org page: https://github.com/coullworks
- Logo = the site **header** lockup (mark + COULLWORKS, no strapline), as transparent SVG:
  - `profile/mark.svg` / `profile/mark-light.svg` — DC shield mark, cream (dark) / graphite (light).
  - `profile/wordmark-dark.svg` / `profile/wordmark-light.svg` — "COULLWORKS" vectorised from the site font (Anton), cream / graphite. `WORKS` stays orange.
  - The README composes mark + wordmark inline via `<picture>` so it's crisp and theme-aware.
- `profile/mark-avatar.png` — 512×512 org avatar (upload in org Settings).

Push to the `.github` repo under the COULLWORKS org to publish the profile.
