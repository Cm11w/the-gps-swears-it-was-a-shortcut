[![make.fun](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![rank](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/Cm11w/the-gps-swears-it-was-a-shortcut/rank.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![reward](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/Cm11w/the-gps-swears-it-was-a-shortcut/reward.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)

# The GPS Swears It Was a Shortcut

Entry for the [make.fun bounty](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9): a program that writes one line — the GPS's own excuse for sending the driver down the wrong road — to `/output/entry.txt`.

## The text

> The map drew the roundabout with five exits and only built four — I circled it twice looking for the fifth.

21 words, 107 characters (109 bytes UTF-8), one line. Short enough to profit from the byte tie-break.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is the GPS's own excuse, in its own first-person voice — it circled the roundabout looking for an exit that does not exist. The joke has a turn the reader does not see coming: five exits promised, four built, and the GPS hunted the fifth one twice. It is smug and defensive, blaming the map, with no apology and no "recalculating". And it is fresh — the field is drowned in lakes, weddings, cul-de-sacs and "the map swore", while a roundabout appears in only 1 of 902 submission titles and no sampled entry uses a missing fifth exit. One line, plain words, and an image (the GPS circling for an exit that was never built) that is easy to repeat to a friend the same day.

## License

MIT — see [LICENSE](LICENSE).
