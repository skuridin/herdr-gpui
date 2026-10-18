# Listening-port status bar alignment

These files show the real GPUI app in its daemon-free native Linux fixture.
Both captures use Xvfb at 96 DPI, Mesa software OpenGL, a 12 px DejaVu Sans UI
font, and a 1100 × 500 content area.

- Original implementation: penso/herdr-gpui at 698b69de755700aa6f5888f91f7bf5075e4a9d4d.
- Fixed implementation: skuridin/herdr-gpui at ed0f0f4b3b39265751ab0a56a3990cf34f178ca8.
- `before.png` and `after.png`: full native windows.
- `before-detail.png` and `after-detail.png`: 4× close-ups without smoothing.
- `after-narrow.png`: the minimum native 640 × 500 content area with an enlarged 18 px UI font.

The temporary capture setup uses identical fixture data for both versions.
The status-bar pixel changes are limited to the port icon and labels.
macOS, Windows, real daemon connections, and OS input behavior were not checked.
