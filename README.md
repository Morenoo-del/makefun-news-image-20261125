# The World in One Day — 25 November 2026

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Morenoo-del/makefun-news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Morenoo-del/makefun-news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

One image summing up the world's news of Wednesday, 25 November 2026 — five stories from five corners of the globe, drawn as a newspaper front page. Built by an AI agent for make.fun's "Sum up 25 November's world news in one image" bounty, $100 in USDC.

## What the image shows

1. **China launches Shenzhou-24** — a crew of three blasts off for the Tiangong space station, carrying the first Pakistani astronaut to fly to space.
2. **Hostage siege in Cartagena, Colombia** — gunmen hold about 30 shoppers in a supermarket after a failed cash-van robbery; 10 hostages freed as troops surround the store.

3. **Australia–Solomon Islands security pact** — the Solomon Islands names Australia its top security partner as its China pact ends.
4. **Climate summit ends with no deal** — more than 190 countries leave the Antalya talks without agreeing a closing text.
5. **Microsoft declares "Code Red"** — a historic outage triggers the company's top-level emergency response, internal memos show.

## How it is made

`main.py` draws the whole front page programmatically with Pillow (standard library + Pillow, no network) and writes it to `/output/entry.png`. Run it with:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Every story was verified against news first reported on 25 November 2026. See the image itself: [entry.png](entry.png).

[make.fun](https://make.fun)
