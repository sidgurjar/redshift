# REDSHIFT

A zen spline flier. Hold to curve up, release to curve down; your flight
path is the spline, drawn as a red trail through a dark sky. Thread the
gates. Fly tight curves to **blueshift** your score multiplier.

Nothing kills you. Misses only break your streak.

**Play:** https://sidgurjar.github.io/redshift/

## Controls

| Input | Action |
|---|---|
| Hold (touch / space / W / up arrow) | curve upward |
| Release | curve downward |
| `C` | toggle the curvature comb + osculating circle |
| `M` | audio on/off |
| `P` | pause |

## Notes

Single self-contained HTML file: no build, no dependencies, no network
requests. Canvas 2D rendering; the synthwave soundtrack is generated at
runtime with the Web Audio API (there are no audio files). The curvature
visualisation is a comb of normals scaled by signed curvature, in the
spirit of Freya Holmer's spline videos.
