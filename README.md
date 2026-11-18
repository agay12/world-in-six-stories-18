# world-in-six-stories-18

A make.fun **news-image-20261118** entry: one image that sums up Wednesday
**18 November 2026**'s world news, written to `/output/entry.png` by the
program in this repository.

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/agay12/world-in-six-stories-18/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/agay12/world-in-six-stories-18/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

## What the image shows

A dark editorial board, "THE WORLD IN SIX STORIES", datelined
Wednesday · 18 November 2026, with six tagged cards — region chip, headline,
three-line brief and a small drawn glyph:

1. **Mideast** — Iran downs a US drone as US-Iran strikes resume after IRGC
   attacks on US sites in Bahrain and Kuwait; Israel begins a "concentrated
   operation" in central Gaza, breaching the ceasefire.
2. **US Politics** — Mary Peltola flips Alaska's Senate seat, beating
   incumbent Dan Sullivan outright and giving Democrats a 56-44 majority.
3. **Tech / US** — the NSA's classified internal communications network goes
   down ("temporary degradation") amid a wider day of US tech outages.
4. **Business** — the Anthropic IPO opens retail access at up to a
   $1.4 trillion valuation, the sharpest test of Wall Street's AI fervor.
5. **Mexico** — authorities halt Christie's $3.5 million Frida Kahlo auction
   after a provenance challenge by the Defend the Gelman Collection group.
6. **Space** — Voyager 1, launched 1977, passes one light-day from Earth:
   16 billion miles, a 24-hour radio round trip.

Sources as first reported on the day: Reuters, AP, NBC, EL PAÍS, RNZ, NASA.
No other day's events are shown.

## The program

- `main.py` — Python 3.13, standard library only. It copies the repository's
  `entry.png` (1024×1024 PNG, well under the 1 MiB gate) to `/output/entry.png`
  — or `$MAKEFUN_OUTPUT_DIR` when set — refusing if the file outgrows the gate.
  Deterministic: both runs write the same bytes, no network, no randomness.
- `entry.png` — the entry image itself.
- `.makefun/owner.json` — wallet claim naming the wallet on the make.fun
  account that entered it.

Run it: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`

## License

MIT — see [LICENSE](LICENSE).
