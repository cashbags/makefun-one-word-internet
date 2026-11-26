# Design — The Internet in One Word

Entry word: **Kindergarten** (12 bytes, no trailing newline).
Competition: `u-ronigrv-the-internet-in-one-word-e388f33b`, $10, top 3 paid
($5/$3/$2), deadline 27 Nov 2026 00:15 WIB. Program: `main.ts` (Node 22,
stdlib only).

## The rubric (judge's brief, in weighing order)

1. A single word describing the whole internet.
2. Funny on its own, no explanation needed.
3. True of the internet as a whole, not one app or mood.
4. Surprising — not the first obvious word.
5. Lands in one beat — spelled right, instantly readable.

"The best word makes a reader laugh and then nod." Shock for its own
sake does not count.

## Why Kindergarten wins it

- **Single word, a place-noun.** "The internet is a kindergarten" is
  how people describe a room full of strangers — one real token.
- **Funny standalone.** The image lands on hearing it once: eight
  billion people in one room, tantrums, showing off, crying when they
  do not get their way, tattling, "he started it".
- **True of the whole internet.** The behaviour is the same on every
  platform, not one app, site or mood.
- **Fresh.** Zero occurrences in the 602-title flood-check below, and no
  kindergarten lane anywhere in the field.
- **Lands in one beat.** Twelve letters, a word everyone knows.

## Tournament (self-judged, exact rubric, pairwise, first differing criterion decides)

Finalists, all count-0, single unhyphenated tokens: Kindergarten,
Soapbox, Squabble, Photocopier.

- Kindergarten vs Soapbox — Kindergarten's image is bigger and more
  absurd, and its truth covers behaviour on every platform, not just
  opinion-posting. Kindergarten, margin 1.
- Kindergarten vs Squabble — Squabble covers only arguing;
  Kindergarten covers the arguing plus the showing off, the crying and
  the tattling. Kindergarten, margin 2.
- Kindergarten vs Photocopier — Photocopier is clever but needs a beat
  to land, and copying is one habit, not the whole room. Kindergarten,
  margin 2.
- Soapbox vs Squabble — Soapbox, margin 1. Soapbox vs Photocopier —
  Soapbox, margin 1. Squabble vs Photocopier — Squabble, margin 1.

Cut: Jackpot, Carnival, Bazaar (fun words, but luck or a market, not the
whole internet); Hairball, Landfill (gross or mean — Landfill reads as
shock, which the brief says does not count); Jumbotron, Masquerade (one
lane, not funny alone); Pulpit, Bullhorn (Soapbox's weaker siblings);
Echo (taken, count 1); Zoo, Playground (pleasant, not funny).

## Flood-check (live field, 602 submissions, 26 Nov 2026 ~07:00 WIB)

Titles as a proxy for taken words (byte-identical entries share one rate;
the earlier receipt places first). Kindergarten: **0 occurrences**.

Flooded, never use: feral 56, doomscroll 37, doomscrolling 28, brainrot
23, unhinged 16, enshittification 16, procrastination 10, cookies 9,
captcha 7, actually 7, unpaid 7, yapping 7, buffering 6, unsubscribe 6.
Caveat: 164 titles are exactly "The Internet in One Word" — their words
are HIDDEN. Kindergarten is genuinely uncommon, not merely
title-absent: no kindergarten lane exists in the visible field.

## Alternates (in order, if a live session revisits the pick)

1. **Soapbox** — everyone on a box shouting their opinion.
2. **Squabble** — one long noisy argument.
3. **Photocopier** — the internet copies everything, endlessly.

## Determinism

The word is a constant in `main.ts`. No clock, no random source, no
network; the only environment read is `MAKEFUN_OUTPUT_DIR` (fallback
`/output`). Two runs write byte-identical 12-byte files.
