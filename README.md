# Sips & Seats

A free browser game for NZ Election Night 2026. Play solo, compete on one shared device or compare scores with friends watching remotely. There are 40 election-night moments. Drinks are always optional.

[**Play Sips & Seats**](https://0x04-guiltyspark.github.io/sips-and-seats/)

## How to play

Enter one name for a solo tick-off game, or two or more names for a shared claiming game.

- **Solo:** tick each moment once to earn its points. Tap a ticked card to undo it. Drink prompts are optional for you.
- **Shared:** the first player to spot a moment claims its card using the player picker. Each card has one owner for the entire game. The claimant earns the points and all other players receive the optional drink penalty. Undo claim asks for confirmation before making the card available again.

Use the toggle at the top to hide ticked or claimed cards. The setting saves automatically; turn it off to see completed cards and undo them. Category, status and search filters work alongside it. Reset view clears the filters and turns the toggle off without changing scores. If one TV moment matches several cards, count one card; separate moments can score separately. Skipping or substituting drinks never costs points.

## Playing remotely

Everyone opens the site and starts their own game. Agree when to stop, then open **Results & compare** and copy your score into your group chat. Enter friends’ reported names and totals to see rankings. Highest points wins; equal totals tie. Comparison scores can be removed and re-entered to update them. There are no accounts, shared rooms or automatic score syncing.

## Your game stays in your browser

Players, claims or ticks, comparison scores and the hide-completed preference save automatically in browser storage. Return using the same browser and address to continue. Clearing site data removes the save. New Game asks for confirmation before resetting it. Storage failures display a warning and play continues in memory.

Original shared-game saves retain their claim owners. Multi-player saves from the independent-board update offer **Restore shared claiming**, with confirmation before conversion. Where several players ticked the same card, the earliest saved tick keeps ownership; equal timestamps go to the first listed player. Duplicate points are removed, while players and comparison scores remain. Cancel leaves the existing save unchanged.

## Hosting

All game code, styles and card data are included in `index.html`, with no dependencies or build step. GitHub Pages publishes the repository root from `main`; pushes to that branch update the public site. The page can also be served by any static web host. There is no backend, analytics or external request dependency.
