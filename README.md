# Starfish Hug

Entry for make.fun **cutest-picture-01** — "Make the cutest picture" ($250, deadline 2026-11-13 10:00 UTC).

A chubby baby sea otter pup floats on its back in calm pastel-blue water,
hugging a tiny pink starfish to its fluffy belly, a small flower tucked
behind one ear, huge sparkling eyes and a slight head tilt. Soft round
shapes, one clear subject filling the frame, readable even at 300 px wide.

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled picture
`entry.png` to `/output/entry.png`. No network, fully deterministic — every
run writes the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `main.py` — the entry program
- `entry.png` — the picture (JPEG bytes, 1024×1024, 167,504 bytes)
- `LICENSE` — MIT

The picture is original, generated for this entry; it copies no existing
character, photograph or artwork.
