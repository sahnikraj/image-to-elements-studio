# Image to Elements Studio (V2 Prototype)

A browser-based design decomposition tool for PNG/JPG.

## Features
- Upload or paste image from clipboard.
- Automatic segmentation into regions/layers.
- Estimated background detection.
- Draggable layer editing on stage.
- OCR pass (Tesseract.js) to tag probable text layers.
- Auto-color palette extraction.
- Per-layer tint/recolor controls.
- Export composite PNG.

## Run locally
Because this is a static project, you can open `index.html` directly.

For best clipboard/OCR behavior, run a local server:

```bash
cd image-to-elements-studio
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy
Deploy as a static site on Netlify (drag-and-drop or Git-linked deploy).

## Known limitations
- Segmentation is heuristic-based, not ML segmentation.
- Complex gradients/noisy backgrounds reduce segmentation quality.
- OCR speed depends on browser/device and image size.
