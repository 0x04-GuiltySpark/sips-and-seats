# Sips & Seats

A free browser game for NZ Election Night 2026. Gather two or more players around one shared device, watch the coverage and compete to spot 40 election-night moments. Drinks are always optional.

[**Play Sips & Seats**](https://0x04-guiltyspark.github.io/sips-and-seats/)

## How to play

1. Enter each player's name and start a game.
2. Watch for moments on the cards. The first player to spot one claims its points.
3. Each card can be claimed once. Agree on the moment together; accidental claims can be undone.
4. Follow the optional drink prompts, substitute something else or skip them entirely. Everyone can still score.

Filter cards by category or claim status, or search for a particular moment. If one TV moment matches several cards, count one card; separate moments can score separately.

## Your game stays in your browser

Players and claims save automatically in browser storage. Return using the same browser and site address to continue. Games do not sync between devices or browsers, and clearing site data removes the save. **New Game** asks for confirmation before resetting it.

The game has no backend, accounts, analytics or external requests. If browser saving is unavailable, a warning appears and the game continues in memory.

## Hosting

All game code, styles and card data are included in `index.html`, with no dependencies or build step. GitHub Pages publishes the repository root from `main`; pushes to that branch update the public site. The page can also be served by any static web host.
