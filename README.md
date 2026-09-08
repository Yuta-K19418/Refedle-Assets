# Refedle-Assets

Rendered media for the [Refedle](https://github.com/Yuta-K19418/Refedle) README —
kept out of the main repository so that regenerating the demo GIFs on a UI change
does not grow `Refedle`'s history with binary blobs.

## Contents

| Path | What |
|---|---|
| `images/*.gif` | TUI/CLI demo GIFs embedded in the Refedle README |

## Do not hand-edit

Everything here is generated. The GIFs come from the VHS tapes in
[`Refedle/docs/vhs/`](https://github.com/Yuta-K19418/Refedle/tree/main/docs/vhs);
`docs/vhs/regen.sh` in that repo renders them and writes straight into this
clone's `images/` directory. To update a GIF, change the tape in `Refedle` and
rerun `regen.sh`, then commit and push here.

The Refedle README references these files by raw URL pinned to `main`
(`https://raw.githubusercontent.com/Yuta-K19418/Refedle-Assets/main/images/<name>.gif`),
so a push to `main` here is all it takes for the README to pick up a new version.
