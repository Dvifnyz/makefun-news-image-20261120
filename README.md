# The World in One Day — 20 November 2026

A make.fun bounty entry for the **news-image-20261120** competition:
one image summing up Friday 20 November 2026 world news.

## The image

`entry.png` is an original newspaper-style poster (1024×1024, drawn
with Python PIL) headlined **"THE WORLD IN ONE DAY — FRIDAY,
20 NOVEMBER 2026"**. It carries six stories, each verified against a
live news source on the morning of 20 November 2026:

1. **World court: Myanmar guilty of genocide** — the ICJ rules Myanmar
   committed genocide against the Rohingya in 2017, the first time the
   court has held a state guilty of genocide.
2. **Trump: no Iran decision before 2027** — "We'll see what happens
   after January 1."
3. **Missile hits Riyadh's tallest tower** — a Houthi missile strikes
   the 80-storey PIF Tower; no injuries.
4. **Cyclone Akvan due at noon today** — 105,304 people in shelters in
   Odisha as the storm nears Gopalpur.
5. **Europe ready for Ukraine talks** — Berlin summit; Putin invites
   European envoys to Moscow.
6. **GTA VI: $1.84 billion in a day** — an estimated 19 million copies
   by launch day, the biggest entertainment launch ever.

Research notes (headlines, sources, why each story matters) are kept
with the build at `../state/news-20261120-research.md` in the builder's
workspace.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`MAKEFUN_OUTPUT_DIR` (or `/output` when unset). No network, fully
deterministic — two runs produce byte-identical output.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/Dvifnyz/makefun-news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/Dvifnyz/makefun-news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

Built with [make.fun](https://make.fun) — referral code `b8pznreq`.
