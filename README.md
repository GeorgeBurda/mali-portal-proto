# Mali Portal — quick prototype

Portrait phone prototype: Mali Empire under Mansa Musa (gold dust, weighed ingots, indigo silk, manuscript gold leaf, Djenne mudbrick). 5×3, 50 lines, bet 100 (line bet 2), balance 10,000 (saved).

Play: https://georgeburda.github.io/mali-portal-proto/

- Tap anywhere to spin, tap again to skip. The i button has the paytable, turbo and balance reset.
- Three pots above the reels fill from their symbols: **Portal** (15 symbols) starts the Portal feature when full; **Expand** and **Gild** (12 each) stay charged until a feature uses them, then reset. Pot fills are saved.
- Portal feature: four stacked 5×3 sets. The bottom set spins (3 respins); the upper sets hold locked gold-dust weights of rising value (about 1–5×, 5–20×, 20–80×, 80–500× bet). A Portal opens the cell directly above (coin collected, the cell starts spinning); Expand opens a locked cell on the same set; Gild raises the locked coins on the set above the frontier by one tier. Opening a cell resets respins to 3. Opening set IV pays the Grand (example value 1000× bet). Max win 5000× bet.
- Cheats: tap a pot to fill it; `?bonus=1&expand=1&gild=1`, `?seed=N`, `?turbo=1`.
- Math (sim 1M base + 20k features per combo): RTP ≈94.3% = base 59.9% + feature 34.4%; feature about 1 in 150 spins.
