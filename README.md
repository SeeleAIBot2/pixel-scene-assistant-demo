# Pixel Scene Assistant Demo

## What it is
A clickable Step 2 demo for `Pixel Scene Assistant`.

It now contains **two layers**:
1. **mock renderer flow** — front-end procedural pixel-scene draft for fast interaction validation
2. **real sample flow** — one embedded example generated through `Nano Banana + pixelization`

## What you can try
- input a scene brief
- click `生成 mock 草稿`
- continue with `变体` / `refine`
- click `加载真实样例`
- view structured Scene Spec
- export Scene Spec JSON
- export full Scene Package (spec + assets + metadata)

## Real sample artifacts
Under `examples/`:
- `real-sample-original.png` — raw generated image from Nano Banana
- `real-sample-preview.png` — pixelized preview after downsample + palette reduction + nearest-neighbor upscale
- `real-sample-spec.json` — structured scene spec
- `real-sample-package.json` — export package with assets + debug metadata

## What it now represents
This is no longer just a UI mock. It is a **hybrid MVP**:
- mock interaction remains usable in a static page
- real generation has been proven in a local executable pipeline
- the page can load a real generated sample artifact

## What it does NOT prove
- no live public backend/API yet
- draft / variant / refine are not yet all wired to real model execution
- no engine/plugin integration yet

## Open locally
Open `index.html` in browser.
