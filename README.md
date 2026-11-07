# Sips & Seats

A free browser bingo game for NZ Election Night 2026. Play solo, share a device or compare scores with friends watching remotely. Tick off 40 election-night moments and aim for the highest score or a full house. Drinks are always optional.

[**Play Sips & Seats**](https://0x04-guiltyspark.github.io/sips-and-seats/)

## How to play

1. Enter your name and start a game. One player is enough; add more if you’re sharing a device.
2. Tick off the moments you spot. Each card scores once per player, and everyone can score the same card. You don’t have to be first. Tap a ticked card again to undo it.
3. If sharing a device, use **Whose board?** to switch between each player’s independent ticks and score.
4. Play for a personal best, aim to tick all 40 moments for a full house, or compare totals with friends. The drink prompts are optional for the person ticking the card; skipping or substituting never costs points.

Filter cards by category or tick status, or search for a particular moment. If one TV moment matches several cards, count one card; separate moments can score separately.

## Playing remotely

Everyone opens the site and starts their own game on their own device. Agree when to stop, then open **Results & compare** and copy your score into your group chat. Enter friends’ reported names and point totals to see the rankings. Highest points wins; equal totals tie. Comparison scores can be removed and re-entered to update them.

There are no accounts, shared rooms or automatic score syncing. Each device keeps its own game and comparison table, and you can return to your board at any time.

## Your game stays in your browser

Players, ticks and comparison scores save automatically in browser storage. Return using the same browser and site address to continue. Games do not sync between devices or browsers, and clearing site data removes the save. **New Game** asks for confirmation before resetting it. Existing games retain their players and earned points when updated to independent boards.

The game has no backend, accounts, analytics or external requests. If browser saving is unavailable, a warning appears and the game continues in memory.

## Hosting

All game code, styles and card data are included in `index.html`, with no dependencies or build step. GitHub Pages publishes the repository root from `main`; pushes to that branch update the public site. The page can also be served by any static web host.
