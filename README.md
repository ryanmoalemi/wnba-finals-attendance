# WNBA Finals Attendance by Game, 2002–2025

An open dataset of published attendance for every WNBA Finals game from 2002 through 2025, compiled by [Full Court Buckets](https://fullcourtbuckets.com) from each game's official WNBA.com box score.

The full interactive table, charts and methodology live on the Full Court Buckets page **[WNBA Finals attendance by year, record and history](https://fullcourtbuckets.com/news/2026-wnba-finals-ratings-tracker/)**.

## Files

| File | Rows | What it is |
|---|---|---|
| `data/wnba-finals-attendance-by-game-2002-2025.csv` | 93 games | One row per Finals game, with date, teams, score, margin, overtime periods, arena, published attendance and a link to the official WNBA.com game record |
| `data/wnba-finals-attendance-2002-2025.csv` | 24 series | One row per Finals series with totals, per-game averages, and single-game highs and lows |
| `data/wnba-finals-attendance-README.csv` | 12 | Variable definitions for the game file |

Published attendance is available for 90 of the 93 games. The three 2020 games were played in the IMG Academy bubble with no fans, so attendance is blank. Because the Finals became best-of-seven only in 2025, per-game averages are a fairer comparison across years than series totals.

## Source and method

Attendance and scores for each game come from that game's official box score on WNBA.com; every row in the game file links to its game record in `source_url`. Series totals and averages are Full Court Buckets calculations. The data was compiled by hand, not scraped.

## Mirrors

- [Hugging Face](https://huggingface.co/datasets/fullcourtbuckets/wnba-finals-attendance)
- [Kaggle](https://www.kaggle.com/datasets/fullcourtbuckets/wnba-finals-attendance-by-year-20022025)

## License and citation

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Free to use and republish (CC0). No credit required.

> Full Court Buckets (Ryan Moalemi), "WNBA Finals attendance by year, 2002–2025," Dataset v1, 2026. https://fullcourtbuckets.com/news/2026-wnba-finals-ratings-tracker/
