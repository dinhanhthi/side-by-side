<p align="center">
  <img src="logo.png" alt="Side by Side - Photo Combiner" width="100" />
</p>

<h1 align="center">Side by Side - Photo Combiner</h1>

<p align="center">
  A simple web tool to combine multiple photos into a single image.
</p>

## Features

- Flexible grids: 2×1, 1×2, 2×2, 3×2, 2×3, 3×3 or custom (up to limit) — not just two photos
- Choose the aspect ratio of the final image (1:1, 4:3, 16:9, 9:16, and more) — applied to the whole composition
- Unified editor: the preview **is** the upload area — drop photos straight into each cell and see the combined result live
- Pan and zoom each photo in place (drag to move, scroll to zoom, double-click to reset)
- Diagonal split option for 2-photo layouts (great for dark/light or before/after)
- Add customizable border (width and color)
- Paste from clipboard, and copy or download the combined result
- Runs entirely in browser - no server uploads
- Modern, beautiful dark UI

## Local Development

Run a local server using one of these methods:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (npx)
npx serve

# Node.js (http-server)
npx http-server -p 8020
```

Then open http://localhost:8000 in your browser.

## Usage

1. Choose a grid layout (2×1, 1×2, 2×2, ...) or type a custom cols × rows
2. Pick an aspect ratio for the final image (or leave it on Auto)
3. Add photos directly in the preview — click, drag & drop, or paste into each cell
4. Fine-tune each photo in place: drag to reposition, scroll to zoom, double-click to reset
5. For 2-photo grids: optionally enable "Diagonal split"
6. Optionally add a border (width and color)
7. Download the result or copy it to the clipboard

## License

MIT
