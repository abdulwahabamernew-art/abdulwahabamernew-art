# Project Visual Assets Plan

This guide defines a consistent visual language for project screenshots, GIFs, and README illustrations.

## Shared visual direction

Use a dark navy background with cyan and violet accents to match the profile banner. Keep each visual focused on one workflow, use a 16:9 canvas for desktop projects, and use a 9:16 or 4:5 canvas for Android screens. Add a small project label in the corner, but do not cover the main result. Prefer real screenshots and real outputs whenever available.

## Hieroglyph OCR

**Recommended filename:** `docs/assets/hieroglyph-ocr-demo.gif`

**Storyboard:** upload an Egyptian hieroglyph image, show YOLO detection boxes, show cropped glyphs, reveal Gardiner-code recognition, then show the annotated output and JSON/ZIP export.

**Caption:**

> End-to-end hieroglyph detection and Gardiner-code recognition with YOLO and TrOCR.

**README snippet:**

```html
<p align="center">
  <img src="docs/assets/hieroglyph-ocr-demo.gif" alt="Hieroglyph OCR detecting glyphs and recognizing Gardiner codes" width="850">
</p>
```

## VisionStudio

**Recommended filename:** `docs/assets/visionstudio-android-demo.gif`

**Storyboard:** open the offline Android app, select a live camera filter, switch to edge detection or thresholding, then show on-device object detection. Include a small `Offline` indicator in the recording if the application has one.

**Caption:**

> Real-time image processing and on-device computer vision running offline on Android.

**README snippet:**

```html
<p align="center">
  <img src="docs/assets/visionstudio-android-demo.gif" alt="VisionStudio Android app applying offline computer vision filters" width="360">
</p>
```

## Sentiment140

**Recommended filename:** `docs/assets/sentiment140-inference.png`

**Storyboard:** use a clean static panel showing one input sentence, the selected model, the predicted sentiment, and a compact comparison between the classical baseline and DistilBERT. Keep exact metrics in the README text or a deterministic chart, not inside an AI-generated decorative image.

**Caption:**

> Reproducible sentiment inference comparing TF-IDF baselines and Transformer-based modeling.

**README snippet:**

```markdown
![Sentiment140 inference and model comparison](docs/figures/sentiment140-inference.png)
```

## Plant Disease Project

**Recommended filename:** `docs/assets/plant-disease-pipeline.png`

**Storyboard:** show the input leaf image, the plant/not-plant gate, the detected leaf crop, disease label, confidence, and annotated output. Use a clearly marked `Example output` label and avoid implying medical or agricultural certainty beyond the model's documented scope.

**Caption:**

> A guarded plant-disease pipeline that rejects obvious non-plant images before classification.

**README snippet:**

```markdown
![Plant disease classification pipeline](docs/assets/plant-disease-pipeline.png)
```

## Algorithm Battle Arena

**Recommended filename:** `docs/assets/algorithm-battle-arena.gif`

**Storyboard:** select two sorting algorithms, start the visualization, show the bars changing, then reveal the benchmark summary with runtime and operation counters. For pathfinding, use a separate GIF rather than mixing two workflows in one visual.

**Caption:**

> Visualize algorithms, run controlled benchmarks, and compare empirical behavior with theoretical complexity.

**README snippet:**

```html
<p align="center">
  <img src="docs/assets/algorithm-battle-arena.gif" alt="Algorithm Battle Arena sorting visualization and benchmark comparison" width="850">
</p>
```

## Capture checklist

Record short clips between 5 and 10 seconds. Crop out personal notifications, API keys, local paths, and unrelated browser tabs. Prefer 1280×720 for desktop captures and 1080×1920 for Android captures. Compress GIFs after recording and keep each file small; if a GIF becomes large, use a short MP4 link or a static PNG preview instead.
