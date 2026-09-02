# Color Wheel Designer

[Try it here!](https://cosmicgraviton.github.io/ColorWheelDesigner/)

A browser tool for designing printable color wheels for the **[ColorComposer HackPack](https://www.crunchlabs.com/products/color-composer)**. Open `index.html` in a browser [here](https://cosmicgraviton.github.io/ColorWheelDesigner/).

The color wheel is a disc you paint, save, and export. Print the SVG at its native **16 cm** size or print the PNG at 300 dpi so the disc and its three alignment notches match the physical player.

## What you can do

- **Paint segments** by selecting a color and clicking the wheel. Shift-click a segment to sample its color.
- **Choose a palette** (Sasha Trubetskoy 20, HSV 8×4, Kelly’s 22, or Tableau 20) or pick any custom hex color.
- **Fill, clear, or migrate** — paint the visible wheel from the palette in sequence, reset every segment to white, or snap existing colors to the nearest swatch in the selected palette.
- **Circles or spiral** — concentric rings (1–8, with a configurable segment count per ring) or a single spiral (12–96 segments, equal-angle or equal-length spacing). Direction can be clockwise or anticlockwise.
- **Overlays** — toggle the three white alignment notches and the black segment borders.
- **Undo / redo** — toolbar buttons or Ctrl/Cmd+Z, Ctrl/Cmd+Shift+Z, and Ctrl/Cmd+Y.



## Saving and exporting


| Button   | Result                                                             |
| -------- | ------------------------------------------------------------------ |
| **Save** | Downloads the wheel as JSON so you can keep working later.         |
| **Load** | Restores a previously saved JSON file.                             |
| **Export**  | Export the color wheel as a Vector (SVG) or Raster (PNG) image. |
