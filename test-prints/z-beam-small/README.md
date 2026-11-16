# Small Z-beam test print

`Z-beam_small_test.stl` is a smaller version of [RepRap Ltd's Infinite-Z-Beam](https://github.com/RepRapLtd/Infinite-Z-Beam),
a printed truss beam designed for infinite-Z belt printers like the CR-30.

It was exported from David Eccles' OpenSCAD version of the beam (`Z-beam.scad` upstream), with
four settings changed from its defaults:

| Setting | Default | This print |
| --- | --- | --- |
| `length` | 200 | 300 |
| `width` | 35 | 25 |
| `holeSize` | 3 | 2 |
| `screwHoleCount` | 12 | 6 |

All other settings are the defaults: `height` 25, `thickness` 3, `diagStyle` "tetra". To make a
different size, edit those settings in the upstream `Z-beam.scad` and export from OpenSCAD.

The beam design and this STL derived from it are GPL-2.0, from upstream, not this repo's MIT
licence.
