# Test Cases - Web Paint

## 1. Startup and layout
- Action: Open the app.
- Expected: Menu bar on top, tool panel on left, white canvas center, palette bottom.

## 2. Pencil tool
- Action: Select pencil and draw freehand.
- Expected: Thin continuous strokes in foreground color.

## 3. Brush and size
- Action: Select brush, increase size slider, draw.
- Expected: Thicker stroke than pencil.

## 4. Eraser tool
- Action: Draw shape, switch to eraser, erase part.
- Expected: Erased pixels become background color.

## 5. Line / rectangle / ellipse
- Action: Draw each shape by drag-release.
- Expected: Live preview while dragging, final shape committed on release.

## 6. Fill bucket
- Action: Draw enclosed shape and use fill inside.
- Expected: Region fills with foreground color.

## 7. Text tool
- Action: Select text tool, click canvas, enter text in prompt.
- Expected: Text drawn at clicked position with selected font size and foreground color.

## 8. Eyedropper
- Action: Pick a pixel color from canvas.
- Expected: Foreground swatch updates to sampled color.

## 9. Undo / redo
- Action: Draw 3 actions, undo twice, redo once.
- Expected: Canvas state moves backward and forward correctly.

## 10. Open / save
- Action: Open an image file. Save canvas as PNG.
- Expected: Imported image appears fitted in canvas; download file is created.

## 11. Palette behavior
- Action: Left-click a color cell, then right-click another color cell.
- Expected: Left-click sets foreground; right-click sets background.

## 12. Zoom
- Action: Change zoom to 200% and 50%.
- Expected: Canvas scales visually while preserving drawing behavior.
