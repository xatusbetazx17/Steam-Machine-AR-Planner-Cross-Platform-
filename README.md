# Steam Machine AR Planner (Cross‑Platform)

This is a cross‑platform AR space‑planner for the **Valve Steam Machine (2026)**.

## Dimensions used (outer)
- Width: 156 mm
- Depth: 162.4 mm
- Height: 152 mm

## How to use
### Recommended: GitHub Pages
1. Upload the folder `steam-machine-ar/` (this package) into a GitHub repo.
2. Enable GitHub Pages for the repo.
3. Open `index.html` on your phone (Safari on iPhone, Chrome on Android).
4. Tap **Open AR**.

### Any HTTPS host works too.

## Notes
- iPhone: AR Quick Look (USDZ) via Safari.
- Android: WebXR / Scene Viewer via Chrome (ARCore supported phones).
- Models are **simple blocks** (to scale) so you can see real desk space.


  # Steam Machine AR Planner+ (More Complex Setups)

Includes presets with:
- Monitor arms (single/dual)
- Cable bundles
- Ultrawide + speakers + webcam
- Hub + external SSD + extra USB cables
- Streaming setup (mic boom arm)
- Network setup (switch, router, UPS, power strip)

Steam Machine outer size used (true-scale):
- 156 mm (W) × 162.4 mm (D) × 152 mm (H)

## Use it
Host over HTTPS (GitHub Pages), open `index.html` on your phone, select a preset, tap **Open AR**.


# Steam Machine AR Planner+ v2

This version adds:
- iPhone Quick Look fragment: `#allowsContentScaling=0` (locks scaling)
- A red "SetupFootprint" plate that shows the total occupied footprint of each preset

Steam Machine size used (true-scale): 156mm (W) × 162.4mm (D) × 152mm (H)

## Most common reasons AR placement feels wrong
1) Not hosted on HTTPS (Android WebXR needs HTTPS)
2) Not using Safari on iPhone / Chrome on Android
3) Surface has low texture or bad lighting

## Use it
Host over HTTPS (GitHub Pages), open `index.html`, choose a preset, tap **Open AR**.
