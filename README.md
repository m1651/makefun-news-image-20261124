# The World in One Day — 24 November 2026

[![news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/m1651/makefun-news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/m1651/makefun-news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

A one-image summary of the world's news of **Tuesday 24 November 2026**,
drawn as a newspaper front page. The program ships the image in this
repository and copies it to the output directory as `entry.png`.

## What the image shows

The masthead names the day in large type — **24 NOVEMBER 2026** — above
six stories from across regions and fields, plus a footer strip:

- **Lead story, tech and markets:** Jensen Huang returns as Nvidia chief
  executive just 11 days after resigning, after Donald Trump intervened.
  Nvidia shares jump 31%, the Nasdaq 6.5% and the S&P 500 4.7%.
- **Climate:** the COP31 summit in Antalya ends with no deal, after the EU
  and others reject a final text with no mention of moving away from
  fossil fuels.
- **War in Ukraine:** Russian strikes kill at least 14 people in the Kyiv
  region; President Zelensky calls for four-way talks with Russia as soon
  as possible.
- **Disaster in Indonesia:** a fire at a candy factory in Banten kills at
  least 24 workers, with about 30 people still missing.
- **Politics in the USA:** Democratic congressman Jimmy Gomez resigns after
  the House Ethics panel finds evidence of sexual misconduct.
- **Asia:** India and Nepal launch the Saryu–Kamala Express train across
  their border.
- **Sport:** Carlos Alcaraz wins his first ATP Finals title, beating
  Alexander Zverev; Rishabh Pant hits 128 in the drawn India–New Zealand
  Test.
- **Also:** US states sue Musk firms over sexualised images made with the
  Grok chatbot; storms threaten Thanksgiving travel; the UN chief calls
  for an AI risk framework within a year; the world chess title match
  opens in Geneva.

## How the image was made

Every pixel is original work drawn in this session with Python (Pillow)
and the DejaVu fonts: the masthead, the globe, the rising bar chart and
every card and label are code-drawn shapes and text. No photograph,
artwork or existing image was downloaded, copied or reused. The finished
image is stored in this repository as `entry.png`.

## Running it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` uses only the Python standard library, needs no network, and
copies `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`. Running it twice
produces byte-identical output: a 1024×1024 PNG of about 160 KB, inside
the competition's 1 MiB and 1024×1024 limits.

## License

MIT — see [LICENSE](LICENSE).
