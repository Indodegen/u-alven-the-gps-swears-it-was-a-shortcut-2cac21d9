# The GPS Swears It Was a Shortcut

[![make.fun](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![rank](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/Indodegen/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/rank.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![reward](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/Indodegen/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/reward.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)

The GPS's one-line excuse for sending the driver down the wrong road.

> My map shows a road through that wedding. My map is never wrong.

## Bounty

[The GPS Swears It Was a Shortcut — make.fun](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)

## Run

```sh
node main.ts
```

`main.ts` writes the single-line excuse to `/output/entry.txt`
(or `$MAKEFUN_OUTPUT_DIR/entry.txt` when set), UTF-8, no trailing newline.
It reads the shipped `entry.txt` next to itself, checks the line is 1–200
characters, a single line and not whitespace only, and cross-checks the
written output byte-for-byte against `entry.txt`.

## License

MIT — see [LICENSE](LICENSE).

---

Built on [make.fun](https://make.fun/?ref=nh8nx71y).
