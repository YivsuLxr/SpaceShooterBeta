# Space Shooter (Beta)

Standalone build of Space Shooter, published separately from the main
portfolio so it can be shared with a direct link.

This repo only ever holds the compiled web build (`index.html`, `index.js`,
`index.wasm`, `index.data`) - no C++ source, no engine, no portfolio page
around it. It's kept in sync by hand: rebuild in the main portfolio repo,
then copy the four build files over here and commit.

## Play

Open `index.html` (served over http/https - it won't load from a plain
`file://` path) or, once this repo is published via GitHub Pages, the live
URL directly.

Optional query params (all have sensible defaults if omitted):
- `?mode=score|infinite|infinite-solo` - which game mode loads on start
  (defaults to `score`, the 90-second solo run).
- `?lang=fr|en` - UI language (auto/defaults to English if omitted).
