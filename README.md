# Web Paint (MS Paint Style)

A browser-based painting app styled like classic MS Paint.

## Implemented features
- Classic desktop-style layout: menu bar, left tools, canvas area, bottom palette.
- Tools: pencil, brush, eraser, line, rectangle, ellipse, fill bucket, text, eyedropper.
- Utility actions: open image, save PNG, clear canvas.
- Edit actions: undo and redo.
- Drawing controls: brush size, text size, zoom.
- Color system: foreground/background swatches, palette with left-click/right-click behavior.

## Run locally
```bash
cd image-to-elements-studio
python3 -m http.server 8080
```
Open `http://localhost:8080`.

## Keyboard shortcuts
- `Ctrl/Cmd + Z`: Undo
- `Ctrl/Cmd + Y`: Redo
- `Ctrl/Cmd + S`: Save PNG
- `Ctrl/Cmd + O`: Open image

## Notes
- Selection tool currently draws selection box only. Full move/crop selection can be added next.
