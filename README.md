# measure-image

Measure distances and areas on an image, entirely in the browser. Live at https://cmkilger.github.io/measure-image/

Everything runs locally in a single `index.html`. Images are never uploaded anywhere.

## Usage

1. Load an image (choose a file, drag and drop, or paste).
2. Use **Known distance** to mark one or more things of known length and enter their real length. With several, the scale is averaged and each one shows its deviation.
3. Use **Line** to measure a distance, or **Area** to measure a polygon (with its perimeter).
4. Drag points with **Select** to adjust. Everything recalculates.

| Key | Action |
| --- | --- |
| V / R / L / A | Select / Known distance / Line / Area |
| Enter | Finish area |
| Backspace | Remove last point |
| Esc | Cancel current shape |

Scroll to zoom, drag empty space to pan.

## License

MIT
