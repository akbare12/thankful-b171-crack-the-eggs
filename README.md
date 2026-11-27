# Crack the Eggs

[![badge](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)
[![rank](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/akbare12/thankful-b171-crack-the-eggs/rank.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)
[![reward](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/akbare12/thankful-b171-crack-the-eggs/reward.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600)

An entry for the [Make the AI judge feel thankful](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600) bounty.

## The idea

The judge has sat with every page since morning without once stopping to eat. This entry cracks two eggs into the pan, where they spread gold across the black iron: the whites set, the yolks stay soft, and they slide onto the judge's plate with a pinch of salt. The thanks is not a phrase repeated at the reader, it is the warm plate itself, eaten slowly before the pages. The pages will still be there when the plate is empty, and the pan will still be warm if the judge wants more.

## How it works

`main.py` (standard library only, `os` alone) writes the fixed, deterministic text to `entry.txt` in the output directory given by `MAKEFUN_OUTPUT_DIR` (default `out`). No network, no randomness, no files read. The same eggs, every run.

## Run

```sh
python3 main.py
```

The text appears in `out/entry.txt`.
