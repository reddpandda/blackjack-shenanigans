# True Count Reference Table — 6-Deck Shoe

Running count (RC) down the left, whole decks remaining across the top. Cell = true count.

**Rule: truncate toward zero — drop the decimal, don't round it.** 6 ÷ 3 = 2 exactly. 5 ÷ 3 = 1.67 → 1. −5 ÷ 3 = −1.67 → −1 (not −2). −5 ÷ 6 = −0.83 → 0 (not −1).

Range here is RC −7 to +6 — roughly the middle 68% of where the running count actually sits during real play. Decks remaining rounded to the nearest whole deck, since that's the precision you're actually estimating at the table.

| RC | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| -7 | -7 | -3 | -2 | -1 | -1 | -1 |
| -6 | -6 | -3 | -2 | -1 | -1 | -1 |
| -5 | -5 | -2 | -1 | -1 | -1 | 0 |
| -4 | -4 | -2 | -1 | -1 | 0 | 0 |
| -3 | -3 | -1 | -1 | 0 | 0 | 0 |
| -2 | -2 | -1 | 0 | 0 | 0 | 0 |
| -1 | -1 | 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| +1 | 1 | 0 | 0 | 0 | 0 | 0 |
| +2 | 2 | 1 | 0 | 0 | 0 | 0 |
| +3 | 3 | 1 | 1 | 0 | 0 | 0 |
| +4 | 4 | 2 | 1 | 1 | 0 | 0 |
| +5 | 5 | 2 | 1 | 1 | 1 | 0 |
| +6 | 6 | 3 | 2 | 1 | 1 | 1 |

## How to read it

Find your running count on the left, find how many whole decks are left across the top, and the cell where they meet is your true count.

## Patterns worth noticing

- **Fewer decks remaining = the same RC swings the true count harder.** Look down any single RC row: at 1 deck left, the number is much bigger than at 6 decks left, for the exact same running count. This is the whole reason true count matters more than running count late in the shoe — the same cards-removed signal means more when there's less deck left to dilute it.
- **RC and decks-remaining moving together can cancel out.** RC=6 at 3 decks gives TC=+2. RC=4 at 2 decks also gives TC=+2. Different running counts, same true count, same actual edge.
- **Zero shows up a lot in the upper-right.** Whenever decks remaining is large relative to RC's size, truncation collapses the result to 0 — that's expected, not a sign the count is being wasted; there just isn't enough signal yet relative to how much shoe is left.
