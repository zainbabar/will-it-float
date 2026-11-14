# Will it float?

A browser version of our SCI 206 buoyancy video (Group 114, University of Waterloo, fall 2026). You guess float or sink for six grocery items, watch each one drop into a tank, and read why it did what it did. A lab section lets you change how much air is inside an item and how much salt is in the water, and the item rises or sinks to match.

Play it: https://zainbabar.github.io/will-it-float/

Each item settles at the depth its average density sets: a sphere is pushed up by the weight of the water it displaces, simulated frame by frame on a canvas. Densities are approximate.

Everything is in `index.html`, with no build step. To run it locally:

```
python3 -m http.server
```
