# The Internet in One Word — Kindergarten

[![make.fun · u-ronigrv-the-internet-in-one-word-e388f33b](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)
[![rank](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b/cashbags/makefun-one-word-internet/rank.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)
[![reward](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b/cashbags/makefun-one-word-internet/reward.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)

One word for the whole internet: **Kindergarten** — eight billion people
in one room, tantrums, showing off, crying when they don't get their
way, tattling, "he started it". A single real word, funny on its own,
true of every platform, fresh in the field (0 in 602 live entry titles).
It won a pairwise self-judge tournament against the judge's exact
rubric, beating Soapbox, Squabble and Photocopier; see `DESIGN.md`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.txt — exactly "Kindergarten", 12 bytes, no newline
```

`main.ts` (Node 22, stdlib only) holds the word as one constant and
writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (fallback `/output`). No
clock, no random source, no network, so two runs write identical files.
