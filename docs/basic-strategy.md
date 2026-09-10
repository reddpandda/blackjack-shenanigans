Basic Strategy Chart — 6-Deck Shoe, H17, DAS, Late Surrender

Ruleset this chart is built for: 6 decks, dealer hits soft 17, double after split allowed, double on any first two cards, resplit to 4 hands, resplit aces allowed, no hitting split aces, player loses only original bet against dealer blackjack, late surrender, blackjack pays 3:2. Source: Wizard of Odds basic strategy engine, transcribed and reorganized here.

## House edge for this ruleset

| Method | House edge | Applies to |
|---|---|---|
| Optimal (composition-dependent, shuffle every hand) | 0.45953% | Best theoretically possible play — deviates from this fixed chart in rare edge cases based on exact remaining cards |
| **Basic strategy with cut card** | **0.48263%** | **This chart** — real shoe play, cut card used, no composition tracking |
| Basic strategy with continuous shuffler | 0.46263% | Same chart, but dealt from a CSM instead of a cut-card shoe |

The number that actually applies to playing this chart as written, at a real table with a normal shoe and cut card, is **0.48263%**. The 0.45953% figure requires deviating from a fixed chart in specific situations based on exact composition — it's the ceiling, not what this table delivers on its own.

## Legend

| Code | Meaning |
|---|---|
| H | Hit |
| S | Stand |
| P | Split |
| Dh | Double if possible, otherwise Hit |
| Ds | Double if possible, otherwise Stand |
| Rh | Surrender if possible, otherwise Hit |
| Rs | Surrender if possible, otherwise Stand |
| Rp | Surrender if possible, otherwise Split |

Never take insurance or "even money" — both are always -EV regardless of ruleset.

## Hard totals

| Player | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | A |
|---|---|---|---|---|---|---|---|---|---|---|
| 5  | H | H | H | H | H | H | H | H | H | H |
| 6  | H | H | H | H | H | H | H | H | H | H |
| 7  | H | H | H | H | H | H | H | H | H | H |
| 8  | H | H | H | H | H | H | H | H | H | H |
| 9  | H | Dh | Dh | Dh | Dh | H | H | H | H | H |
| 10 | Dh | Dh | Dh | Dh | Dh | Dh | Dh | Dh | H | H |
| 11 | Dh | Dh | Dh | Dh | Dh | Dh | Dh | Dh | Dh | Dh |
| 12 | H | H | S | S | S | H | H | H | H | H |
| 13 | S | S | S | S | S | H | H | H | H | H |
| 14 | S | S | S | S | S | H | H | H | H | H |
| 15 | S | S | S | S | S | H | H | H | Rh | Rh |
| 16 | S | S | S | S | S | H | H | Rh | Rh | Rh |
| 17 | S | S | S | S | S | S | S | S | S | Rs |
| 18 | S | S | S | S | S | S | S | S | S | S |
| 19 | S | S | S | S | S | S | S | S | S | S |
| 20 | S | S | S | S | S | S | S | S | S | S |
| 21 | S | S | S | S | S | S | S | S | S | S |

## Soft totals

| Player | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | A |
|---|---|---|---|---|---|---|---|---|---|---|
| 13 (A,2) | H | H | H | Dh | Dh | H | H | H | H | H |
| 14 (A,3) | H | H | H | Dh | Dh | H | H | H | H | H |
| 15 (A,4) | H | H | Dh | Dh | Dh | H | H | H | H | H |
| 16 (A,5) | H | H | Dh | Dh | Dh | H | H | H | H | H |
| 17 (A,6) | H | Dh | Dh | Dh | Dh | H | H | H | H | H |
| 18 (A,7) | Ds | Ds | Ds | Ds | Ds | S | S | H | H | H |
| 19 (A,8) | S | S | S | S | Ds | S | S | S | S | S |
| 20 (A,9) | S | S | S | S | S | S | S | S | S | S |
| 21 (A,10) | S | S | S | S | S | S | S | S | S | S |

## Pairs

| Player | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | A |
|---|---|---|---|---|---|---|---|---|---|---|
| 2,2 | P | P | P | P | P | P | H | H | H | H |
| 3,3 | P | P | P | P | P | P | H | H | H | H |
| 4,4 | H | H | H | P | P | H | H | H | H | H |
| 5,5 | Dh | Dh | Dh | Dh | Dh | Dh | Dh | Dh | H | H |
| 6,6 | P | P | P | P | P | H | H | H | H | H |
| 7,7 | P | P | P | P | P | P | H | H | H | H |
| 8,8 | P | P | P | P | P | P | P | P | P | Rp |
| 9,9 | P | P | P | P | P | S | P | P | S | S |
| 10,10 | S | S | S | S | S | S | S | S | S | S |
| A,A | P | P | P | P | P | P | P | P | P | P |
