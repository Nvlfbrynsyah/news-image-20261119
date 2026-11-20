# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Nvlfbrynsyah/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Nvlfbrynsyah/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

## Thursday in one image

This image sums up world news on Thursday 19 November 2026, with a map-led front page linking nine stories across seven places.

- **1 Shenzhen:** Trump, Xi and Putin meet for a first trilateral.
- **2 Kuwait · 3 Bahrain · 4 Qeshm:** Iran widens Gulf attacks; US hit back on Qeshm.
- **5 Crimea:** Crimean Bridge attacked again.
- **6 Washington:** Jeffries set to be first Black Speaker.
- **7 India coast:** Cyclone Akvan nears India's east coast.
- **GTA VI:** the global rollout returns players to Vice City after a 13-year wait.
- **Voyager 1:** reaches one light-day from Earth.
- **Fed minutes:** more hikes likely if inflation stays hot.
- **Van Gogh:** sells for a record $190.4m.

## How it is built

The poster is authored in `poster.html` with inline CSS and SVG. A screenshot of the 1024 × 1024 poster becomes `entry.png`; `main.ts` copies it to the output directory.

Sources: BBC, Reuters, AP, NYT.

## Run it

Render `poster.html` as a 1024 × 1024 browser screenshot and save it as `entry.png`. Run `main.ts` with Node 22 ESM and set `MAKEFUN_OUTPUT_DIR` to the desired output directory; it creates that directory and copies the image there.
