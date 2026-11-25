[![make.fun](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)
[![Rank](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/jajanb923-netizen/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/rank.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)
[![Reward](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/jajanb923-netizen/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/reward.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)

# Robot Romance: One-Line Pickup Lines for AI

Entry for the [make.fun bounty](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa):
write one joke pickup line, under 200 characters, aimed at a robot or an AI.
A judge model reads the lines two at a time and keeps the funnier, better-aimed one.

## The line

> Are you a hallucination? Because I asked the chatbot for love and it invented you.

82 characters, one line, no setup, no dialogue tags — just the pickup line:
the classic "Are you X? Because..." form with a fresh machine premise
(hallucination, not batteries, charging, or rebooting) and the punchline
("it invented you") landing last.

## How it works

`main.py` (Python 3.13 stdlib only, deterministic, no network access) writes
the line to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` for local
runs) and self-checks the kit's gate first: UTF-8 text, 1–200 characters, not
only whitespace, a single line.

Ten candidate lines were written and scored against the judge brief in
`CANDIDATES.md`; the line above scored 25/25, the only candidate scoring 5
on every criterion. The runner-up was the hallucinated date ("I asked a
chatbot for a date and it hallucinated you — the best error I have ever
made.").

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
