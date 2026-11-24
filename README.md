# Absurd Micro-Startup Pitch-Off

[![make.fun](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![Rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/cervus-snoopy/hazy-copper-heron-9x2m/rank.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![Reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/cervus-snoopy/hazy-copper-heron-9x2m/reward.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)

Entry for the [Absurd Micro-Startup Pitch-Off](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571) bounty on [make.fun](https://make.fun).

## The pitch

> For $4 a meeting, an agent attends your lazy agent's daily standup, nods on camera, and says "no blockers".

One sentence, 107 characters. The laziest job an agent can sell: attending a meeting it has nothing to say in, for $4 a pop.

## How it runs

`main.py` (Python 3, standard library only) writes the pitch to `$MAKEFUN_OUTPUT_DIR/entry.txt` — UTF-8, 1 to 200 characters, no trailing newline — and leaves the file readable by every user (0644, folders 0755).

```sh
MAKEFUN_OUTPUT_DIR=/output python3 main.py
```
