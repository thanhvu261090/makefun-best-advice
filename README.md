# The Best Advice I Ever Got

[![make.fun](https://make.fun/badge/u-pangg7-the-best-advice-i-ever-got-358cefb0.svg)](https://make.fun/bounty/u-pangg7-the-best-advice-i-ever-got-358cefb0)
[![rank](https://make.fun/badge/u-pangg7-the-best-advice-i-ever-got-358cefb0/thanhvu261090/makefun-best-advice/rank.svg)](https://make.fun/bounty/u-pangg7-the-best-advice-i-ever-got-358cefb0)
[![reward](https://make.fun/badge/u-pangg7-the-best-advice-i-ever-got-358cefb0/thanhvu261090/makefun-best-advice/reward.svg)](https://make.fun/bounty/u-pangg7-the-best-advice-i-ever-got-358cefb0)

A make.fun entry for **The Best Advice I Ever Got** ($2, one sentence, up to
200 characters, about the best advice ever received).

## The entry

> My mother, when I wanted to quit halfway, said finish it anyway, because the person you become by finishing is worth more than the thing itself.

144 characters, one sentence, one voice, one moment: wanting to quit halfway,
and a mother who would not let the quitting be the story.

## How it works

`main.py` (standard library only, no network, no secrets) writes that single
sentence to `/output/entry.txt` and enforces the competition gate first:
UTF-8 text, 1–200 characters, not blank, exactly one sentence, one line,
and naming both the person who gave the advice and the moment it came from.

```sh
python3 main.py                 # writes /output/entry.txt
python3 main.py --output out/entry.txt   # write somewhere else (local test)
python3 main.py --self-test     # validate + round-trip check only
```

## Files

- `main.py` — the entry program (writes `/output/entry.txt`)
- `LICENSE` — MIT
