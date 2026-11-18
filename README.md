# A virus builds itself

Bacteriophage T4 assembling itself and infecting an *Escherichia coli* cell, rendered in raw WebGL2 in a single `index.html` with no libraries or assets.

The sequence: capsid and tail assemble, DNA is packed into the head, head joins tail, the six long tail fibres attach, the virus lands, the fibres pin, the sheath contracts and the DNA is injected.

## Controls

- Drag to orbit, scroll to zoom, space to pause, arrow keys to step, `L` to toggle labels.
- The scrub bar jumps to any stage. Sound starts muted; use "Enable sound".

## URL parameters

- `?t=<seconds>` freezes the animation at that time, for example `?t=32.65` (mid-contraction).
- `?view=<name>` picks a camera: `head`, `tail`, `baseplate`, `top`, `wide`, `side`, `whole`.
- `?labels=0` starts with labels off.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```
