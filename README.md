# Last Text at One Percent

[![make.fun](https://make.fun/badge/u-azazex-last-text-at-one-percent-ba9fc876.svg)](https://make.fun/bounty/u-azazex-last-text-at-one-percent-ba9fc876)
[![Rank](https://make.fun/badge/u-azazex-last-text-at-one-percent-ba9fc876/intan151/makefun-last-text-one-percent-01/rank.svg)](https://make.fun/bounty/u-azazex-last-text-at-one-percent-ba9fc876)
[![Reward](https://make.fun/badge/u-azazex-last-text-at-one-percent-ba9fc876/intan151/makefun-last-text-one-percent-01/reward.svg)](https://make.fun/bounty/u-azazex-last-text-at-one-percent-ba9fc876)

Entry for the [Last Text at One Percent](https://make.fun/bounty/u-azazex-last-text-at-one-percent-ba9fc876) bounty on make.fun.

## What it does

`main.py` is deterministic, uses no network and no randomness. It writes
exactly one funny final text message, in the voice of a dying phone at
one percent battery, to `/output/entry.txt`:

> 1%. before i go: your 3am 'u up?' texts to your ex are all screenshotted in a folder called 'evidence'. you're welcome. now go find a charger, coward.

The line is 150 characters, a single line — inside the gate of 1–200
characters from `RULES.txt`. A built-in self-check asserts the output
equals the intended entry and stays within the gate.

## Run

```sh
python3 main.py
cat /output/entry.txt
```
