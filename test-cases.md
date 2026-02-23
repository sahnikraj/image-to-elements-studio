# Test Cases - Web Paint Studio

## 1. Layout and startup
- Open app in desktop browser.
- Expect classic paint layout with menu bar, toolbar, canvas, color palette, status bar.

## 2. Freehand drawing
- Use pencil, brush, and eraser with different sizes.
- Expect smooth drawing, eraser uses background color, no console errors.

## 3. Airbrush
- Select airbrush and drag around canvas.
- Expect sprayed dot pattern with current foreground color.

## 4. Shape drawing
- Draw line, rectangle, ellipse, rounded rectangle.
- Test all shape modes: Outline, Fill, Fill + Outline.

## 5. Fill bucket tolerance
- Create gradient/noisy area and fill with low/high tolerance values.
- Expect broader fill at higher tolerance.

## 6. Text and eyedropper
- Place text with selected font size.
- Pick colors from canvas using eyedropper.

## 7. Selection workflow
- Create selection rectangle and move it.
- Copy/cut/paste/delete selection using menu and keyboard shortcuts.

## 8. Clipboard image paste
- Copy an external image and press Ctrl/Cmd+V.
- Expect pasted image appears as movable selection.

## 9. Undo/redo history
- Perform multiple edits and test undo/redo repeatedly.
- Expect deterministic history behavior.

## 10. Image transforms
- Flip horizontal, flip vertical, rotate 90° right.
- Validate orientation changes as expected.

## 11. Filters
- Apply invert colors and grayscale.
- Confirm visual output is correct.

## 12. Canvas resize
- Resize canvas to larger and smaller dimensions.
- Confirm existing drawing is retained/cropped correctly.

## 13. File operations
- Open local image.
- Save PNG and JPG.
- Verify downloaded files are valid and include visible content.

## 14. Zoom and grid
- Test zoom levels 50% to 800%.
- Toggle grid and confirm it appears only at high zoom.

## 15. Mobile basic check
- Open on mobile browser.
- Ensure layout remains functional (single-column tools allowed).
