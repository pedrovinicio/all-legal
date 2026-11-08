# all-legal

Support and privacy pages for all of Pedro's games, served with GitHub Pages from `main` (root).
One folder per game, so a new game doesn't need its own legal repo.

| Game | Support URL | Privacy URL |
|---|---|---|
| Riot Racers | https://pedrovinicio.github.io/all-legal/riot-racers/support.html | https://pedrovinicio.github.io/all-legal/riot-racers/privacy.html |

## Adding a game

1. Copy `riot-racers/` to `<game-slug>/` and rewrite `index.html`, `support.html` and `privacy.html` for the new game
   (what it stores, which SDKs collect data, purchases).
2. In `support.html`, point "Open an issue" at
   `https://github.com/pedrovinicio/all-legal/issues/new?title=%5B<Game%20Name>%5D%20` so issues are tagged by game.
3. Add a row to the table above and a line to the root `index.html`.
4. Use `https://pedrovinicio.github.io/all-legal/<game-slug>/...` in App Store Connect (Support URL, Privacy Policy URL)
   and in the AdMob consent message's privacy URL.

## History

`riot-racers/` was moved here from `pedrovinicio/riot-racers-legal` (Nov 2026). That repo stays online until every
store listing and the AdMob consent message point here, since the Riot Racers 1.0/1.1 listings still use its URLs.
