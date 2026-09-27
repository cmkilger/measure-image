# measure-image

Measure distances and areas on an image, entirely in the browser. Live at https://cmkilger.github.io/measure-image/

Everything runs locally in a single `index.html`. Images are never uploaded anywhere.

Images and measurements are saved in the browser (IndexedDB), so they're still there after a refresh. The most recent image opens on load, and the toolbar dropdown switches between saved images. **Clear measurements** removes the data but keeps the image. **Delete image** removes both. Clearing site data in the browser also removes saved images.

## Usage

1. Load an image (choose a file, drag and drop, or paste).
2. Use **Known distance** to mark one or more things of known length and enter their real length. With several, the scale is averaged and each one shows its deviation.
3. Use **Line** to measure a distance, **Path** to measure a multi-point distance, or **Area** to measure a polygon (with its perimeter).
4. To reuse a scale from another saved image, pick it in **Copy scale from…** under Known distances. This copies the number, not the lines, and it only applies while the image has no known distances of its own. It's only valid when both images share the same pixels-per-distance.
5. Drag points with **Select** to adjust. Everything recalculates.

| Key | Action |
| --- | --- |
| V / R / L / P / A | Select / Known distance / Line / Path / Area |
| Enter | Finish path or area |
| Backspace | Remove last point |
| Esc | Cancel current shape |

Finish a path or area by double-clicking, pressing Enter, or clicking **Finish**; a click on an area's first point also closes it.

Scroll to zoom, drag empty space to pan.

## License

MIT
