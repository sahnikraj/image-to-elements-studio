# Test Cases

## 1. Upload image
- Action: Upload PNG and JPG files.
- Expected: Image loads, status updates, no JS errors.

## 2. Clipboard paste
- Action: Copy image and paste via Ctrl/Cmd+V.
- Expected: Image loads from clipboard.

## 3. Segmentation
- Action: Click `Detect Elements`.
- Expected: Layer list appears, stage shows draggable extracted elements.

## 4. Drag and drop
- Action: Drag 3-4 layers around the stage.
- Expected: Layer position updates smoothly.

## 5. Palette apply
- Action: Select a layer and click palette colors.
- Expected: Selected layer recolors (tinted output).

## 6. Tint strength slider
- Action: Move slider from 0 to 100 for selected layer.
- Expected: Color intensity changes progressively.

## 7. OCR
- Action: Click `Run OCR on Regions`.
- Expected: Some layers tagged as `text` with confidence and extracted text.

## 8. Layer ordering
- Action: Use `Bring Front` and `Send Back`.
- Expected: Stacking order changes in stage.

## 9. Export
- Action: Click `Export Composite PNG`.
- Expected: Downloaded PNG reflects current layer positions and colors.

## 10. Performance
- Action: Test with large image (~4K).
- Expected: App remains responsive; status messages show progress.
