# news-image-20261124

[![make.fun competition](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![make.fun rank](https://make.fun/badge/news-image-20261124/Jhoni1098/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![make.fun reward](https://make.fun/badge/news-image-20261124/Jhoni1098/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124)

One image summing up the world's news of Tuesday, 24 November 2026: the US
blacklists Megaspeed, the cloud firm at the heart of the Nvidia scandal;
Moscow warns Estonia its actions are "on the verge of triggering open war";
a US Senate panel probes JD Vance's ties to a Venezuelan oil contract; the
drone-hit Russian cargo ship Sparta II reaches St Petersburg; Trump pauses
the Iowa detonation of unstable explosives; Pacific nations voice despair as
COP31 ends with no deal; and an O'Hare ground stop snarls Thanksgiving
travel.

Built for the [make.fun competition](https://make.fun/bounty/news-image-20261124)
of the same name. `main.py` (Python 3.13, standard library only) draws the
1024x1024 newspaper front page from scratch — raster canvas, embedded
bitmap fonts, hand-rolled PNG encoder — and writes it to the output
directory. No network, no clock, no randomness: two runs write
byte-identical files. `entry.png` beside it is the rendered output, kept
for preview.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```
