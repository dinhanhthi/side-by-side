<p align="center">
  <img src="logo.png" alt="Side by Side - Photo Combiner" width="100" />
</p>

<h1 align="center">Side by Side - Photo Combiner</h1>

<p align="center">
  A simple web tool to combine two photos into one image.
</p>

## Features

- Flexible grids: 2×1, 1×2, 2×2, 3×2, 2×3, 3×3 or custom (up to limit)
- Diagonal split option for 2-photo layouts (great for dark/light or before/after)
- Add customizable border (width and color)
- Download the combined result
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

1. Upload photos by clicking or dragging (number depends on grid)
2. Choose grid layout (2×1, 1×2, 2×2, ...) or type custom cols × rows
3. For 2-photo grids: optionally enable "Diagonal split"
4. Optionally add a border
5. Preview updates live
6. Download the result or copy to clipboard

## License

MIT
