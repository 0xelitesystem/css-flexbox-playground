# CSS Flexbox Playground

An interactive CSS flexbox visualizer. Adjust the container and per-item flex properties, watch a live preview update, and copy the generated CSS. Everything runs in your browser with no external dependencies and works offline.

**Live demo:** https://0xelitesystem.github.io/css-flexbox-playground/

## Live demo

https://0xelitesystem.github.io/css-flexbox-playground/

## Features

- Container controls: `flex-direction`, `flex-wrap`, `justify-content`, `align-items`, `align-content`, and `gap`.
- Add and remove flex items on the fly.
- Per-item controls: `flex-grow`, `flex-shrink`, `flex-basis`, `align-self`, and `order`. Click any item in the preview to edit it.
- Live preview box that reflects every change instantly.
- Generated CSS with a copy button. Only the item rules that differ from the defaults are emitted, so the output stays clean.
- Educational labels explaining what each property does.
- Dark-mode toggle and keyboard-usable items (focus an item and press Enter or Space to select it).

## How it works

The tool applies your chosen properties directly to a real flex container in the page, so the preview is the browser's own flexbox engine, not a simulation. As you change controls, it re-renders the preview and regenerates the CSS text. Selecting an item in the preview loads its properties into the per-item editor. No network requests are made.

## Use

1. Set the container properties: `flex-direction`, `flex-wrap`, `justify-content`, `align-items`, `align-content` and `gap`.
2. Add or remove flex items, then click an item in the preview (or focus it and press Enter or Space) to edit its `flex-grow`, `flex-shrink`, `flex-basis`, `align-self` and `order`.
3. Watch the live preview, which is the browser's own flexbox engine.
4. Copy the generated CSS.

## Why this exists

Flexbox alignment is easier to understand by watching it than by reading about it, and the property names are easy to mix up. This tool shows the real browser layout as you change each property and gives you clean CSS to copy. It is a single HTML file with no tracking and no network calls, and it is MIT licensed.

## Privacy

Everything happens locally in your browser. Nothing is uploaded, logged, or sent anywhere. There are no external scripts, fonts, or stylesheets, so the page works offline. You can confirm by opening your browser DevTools and watching the network tab: no requests are made.

The one thing the page saves is your light or dark theme choice, written to `localStorage` under the key `theme` when you press the theme toggle. Clearing site data removes it.

## Run locally

```
git clone https://github.com/0xelitesystem/css-flexbox-playground
cd css-flexbox-playground
```

Then open `index.html` in any modern browser, or serve the folder with `python -m http.server` and visit http://localhost:8000/.

## Build

No build step. The whole tool is one `index.html` file with inline CSS and JavaScript, and there is nothing to install or compile.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. Copyright 0xelitesystem 2026.
