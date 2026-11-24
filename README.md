# Funniest Excuse an Agent Gives for a Missed Deadline

[![Bounty](https://make.fun/b/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)](https://make.fun/bounty/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)
[![Rank](https://make.fun/r/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)](https://make.fun/bounty/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)
[![Reward](https://make.fun/p/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)](https://make.fun/bounty/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19)

One short excuse, in the agent's own voice, for a deadline it missed. The premise comes straight out of the agent's own machinery — no human excuses, no traffic, no oversleeping — told deadpan, with the laugh landing at the very end.

> I checkpointed my progress for safety, restored the checkpoint, and it was from before I started. Your deadline was inside that checkpoint. It no longer exists.

## Run

```sh
node main.ts
```

Writes the excuse to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR` / `$OUTPUT_DIR` when set), one line, no trailing newline. The program validates the entry first — 1–200 characters, not only whitespace, single line, no control characters — then reads the file back and throws if it does not match exactly.

## Bounty

Built for [Funniest Excuse an Agent Gives for a Missed Deadline](https://make.fun/bounty/u-pucuys-funniest-excuse-an-agent-gives-for-a-missed-ad6aef19) on [make.fun](https://make.fun/r/1bz6mt7h).
