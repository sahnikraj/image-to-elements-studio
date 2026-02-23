# Web Paint Studio (Classic MS Paint Style)

A browser-based paint app inspired by classic MS Paint UI and interactions.

## Core features implemented
- Classic windowed layout with title bar, menu bar, left tool panel, central canvas, and bottom palette.
- Drawing tools: pencil, brush, airbrush, eraser, line, rectangle, ellipse, rounded rectangle.
- Utility tools: fill bucket (with tolerance), text, eyedropper, selection tool.
- Selection workflow: drag selection, move selection, copy/cut/paste selection, delete selection.
- File actions: new, open image, save PNG, save JPG, paste image from clipboard.
- Edit actions: undo/redo with history snapshots.
- Image actions: resize canvas, flip horizontal/vertical, rotate 90° right, clear image.
- Color actions: swap FG/BG, custom color picker, invert colors, grayscale.
- View actions: zoom controls, pixel grid toggle.
- Keyboard shortcuts for common actions.

## Run locally
```bash
cd image-to-elements-studio
python3 -m http.server 8080
```
Open `http://localhost:8080`.

## Shortcuts
- `Ctrl/Cmd + N`: New
- `Ctrl/Cmd + O`: Open
- `Ctrl/Cmd + S`: Save PNG
- `Ctrl/Cmd + Z`: Undo
- `Ctrl/Cmd + Y`: Redo
- `Ctrl/Cmd + C`: Copy selection
- `Ctrl/Cmd + X`: Cut selection
- `Ctrl/Cmd + V`: Paste selection or clipboard image
- `Delete`: Delete selection
- `G`: Toggle pixel grid
- `X`: Swap foreground/background colors

## Next layer of enhancements
- Lasso/free-form selection.
- Resize and rotate selected region.
- Polygon and curve tools.
- Multi-step action replay / macro recording.
