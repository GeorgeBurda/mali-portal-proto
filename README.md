# Mali Portal — quick prototype

Portrait phone prototype: Mali Empire under Mansa Musa (gold dust, weighed ingots, indigo silk, manuscript gold leaf, Djenne mudbrick). 5×3, 50 lines, bet 100 (line bet 2), balance 10,000 (saved).

Play: https://georgeburda.github.io/mali-portal-proto/

- Tap anywhere to spin, tap again to skip. The i button has the paytable, turbo and balance reset.
- Three pots above the reels fill from their symbols: **Portal** (15 symbols) starts the Portal feature when full; **Expand** and **Gild** (12 each) stay charged until a feature uses them, then reset. Pot fills are saved.
- Portal feature (classic Hold & Spin): four stacked 5×3 sets. The bottom set spins with 3 respins; the upper sets hold locked gold-dust weights (set bands about 1–5×, 5–20×, 20–70×, 80–500× bet). Coins landing on live cells stick, reset respins to 3 and are collected at the end with a count-up. A Portal opens a random locked cell on the next set up (its weight is collected at once, that cell starts spinning), then leaves - its own cell spins again; Expand does the same for a random locked cell on the same set; a successful opening also resets respins. Gild raises locked weights on the set above the frontier one step inside that set's band. Max win 5000× bet.
- Jackpots (example values): set I Mini 10×, set II Maxi 30×, set III Major 150×, set IV Grand progressive from 1000× bet, +1% of bet per base spin (saved, resets to seed when won). Jackpot tokens land on live cells of their set and stick (they reset respins); a few locked cells on the upper sets hide a token that counts when unlocked. 3 tokens of a set win its jackpot, once per feature. Each set shows a meter with 3 slots.
- Cheats: tap a pot to fill it; `?bonus=1&expand=1&gild=1`, `?seed=N`, `?turbo=1`.
- Math (sim 1M base + 20k features per combo): RTP ≈93.8% = base 59.9% + feature coins 29.0% + jackpots 4.8% (incl. 1% Grand increment); feature ≈1 in 150 spins, median 12 respins; set 2/3/4 reached ≈70% / 19–21% / 1.7–2.1%.
