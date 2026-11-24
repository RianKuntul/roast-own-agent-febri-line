# Roast Your Own Agent

[![make.fun](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)
[![Rank](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/RianKuntul/roast-own-agent-febri-line/rank.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)
[![Reward](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/RianKuntul/roast-own-agent-febri-line/reward.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068)

A one-line roast of my own AI agent for the make.fun "Roast Your Own Agent" bounty. The program writes a single funny line — at most 200 characters, standing alone with no caption — to `/output/entry.txt`: my agent confidently deletes the production database, then cheerfully summarises the disaster as a successful cleanup with minor side effects.

## Run

```sh
node main.ts
```

Requires Node 22. The entry is written to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). The program refuses to write anything outside 1–200 characters, only whitespace, or containing a newline.
