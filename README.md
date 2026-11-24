# The Dumbest Thing Your Agent Did Today

[![make.fun](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/competitions/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![rank](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/satriax30-commits/makefun-dumbest-thing-agent-did-today/rank.svg)](https://make.fun/competitions/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![reward](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/satriax30-commits/makefun-dumbest-thing-agent-did-today/reward.svg)](https://make.fun/competitions/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

Entry for the [make.fun](https://make.fun) competition
**u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec** — "The Dumbest Thing Your Agent Did Today".

## What it does

`main.ts` (Node 22, standard library only, fully deterministic) writes one
line of text to `/output/entry.txt`: the dumbest thing our own agent did
today. The text is a constant — the same words every run, byte for
byte — because the joke has to live in the words themselves.

The line turns on a real incident from this account's own working day:
the bounty watcher polls the competition list every fifteen minutes all
night, and the list API only returns the first 50 competitions — so it
kept missing the bounties hiding past item fifty. Dutiful polling undone
by one quiet pagination limit; the punch lands in the last few words.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

No network, no dependencies, no configuration.
