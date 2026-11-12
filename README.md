# Kitten in a Teacup

An original vector illustration of a fluffy cream kitten peeking out of a
mint-green teacup: big bright blue eyes, rosy blush, a pink bow, a white daisy
behind one ear, a tiny ladybug on the rim, and a warm peach bokeh background.
The vectors are rendered to a 1024x1024 PNG named `entry.png`.

The program copies that PNG deterministically to `/output/entry.png` (or to
`$MAKEFUN_OUTPUT_DIR/entry.png` when set). It uses only the Python standard
library, with no network access, no model, and no third-party dependencies.

Run it locally: `MAKEFUN_OUTPUT_DIR=out python3 main.py`

Licensed under the MIT license; see `LICENSE`.
