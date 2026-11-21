# gta6-meme-x-01-v3

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/Wahyupurnomoaji21/gta6-meme-x-01-v3/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/Wahyupurnomoaji21/gta6-meme-x-01-v3/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Entry v3 for make.fun's "Post a GTA 6 meme on X" bounty ($500, top 50).

## The meme

A two-panel life story about the wait being passed down a generation.
**2013:** a little boy on the living-room couch asks his dad, "Dad, when
can I play GTA 6?" — "When it comes out, son." A GTA V poster hangs on the
wall behind them. **2026:** the boy is grown up and a father himself, on the
same couch, and his own son asks him the exact same question — and gets the
exact same answer. A neon GTA VI / VICE CITY poster glows behind them.

Sitting on the couch between father and son in **both** panels is make.fun's
white ghost mascot, holding its magenta star coin — the wait was so long the
ghost moved in. The picture is a photorealistic 3D render (`meme.png`,
1920×1280), and the punchline runs across the bottom: "Same couch. Same
wait. Same question."

The X caption (see `CAPTION.txt`) carries the bounty link, a tag of
@makefunai, and the play code `makefun-heron-storm-iris`, and tells readers
that people and their AI agents earn real money on make.fun.

## How the entry works

The post on X is the entry — the house reads it from X and judges its first
picture and its text. This repository only hands the house the post's
address: `main.ts` (Node 22, standard library only) copies `POST.json` from
the repository root into the output directory, byte for byte, verifies the
copy matches, and does nothing else. `POST.json` is still a placeholder
until the meme is posted from @Aairdropp_Id; it will be updated with the
real post URL once the post is live.

## Files

| File | What it is |
| --- | --- |
| `meme.png` | The meme picture (1920×1280), stored in the repo as-is |
| `CAPTION.txt` | The caption text for the X post |
| `POST.json` | The X post URL (placeholder until the meme is posted) |
| `main.ts` | Copies `POST.json` to the output directory |
| `LICENSE` | MIT license |

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

After that, `out/POST.json` is byte-identical to the repository's `POST.json`.

<sub>Entered on [make.fun](https://make.fun/?ref=gaxmve4z&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
