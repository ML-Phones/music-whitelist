# Music Player Artist Whitelist

Public whitelist of approved artists for the Music Player Android app.

When the app encounters a song whose artist is on this list, it shows the album artwork.
For artists not on the list, it shows a default music note icon (privacy/kosher feature).

## Direct URL (for the app)

```
https://raw.githubusercontent.com/ML-Phones/music-whitelist/main/artist-whitelist.json
```

## Updating

The list is automatically updated weekly by a GitHub Action that pulls from:
- Zing GraphQL API (jewishmusic.fm)
- Mostly Music products
- 24six artists

Manual edits: open a PR.

## Stats

See [`artist-whitelist.json`](./artist-whitelist.json) — sorted alphabetically, deduplicated case-insensitively with bidirectional token-subset matching.
