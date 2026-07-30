# CSS Flexbox Playground

An interactive CSS flexbox visualizer. Adjust the container and per-item flex properties, watch a live preview update, and copy the generated CSS. Everything runs in your browser with no external dependencies and works offline.

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

## Privacy

Everything happens locally in your browser. Nothing is uploaded, logged, or sent anywhere. There are no external scripts, fonts, or stylesheets, so the page works offline. You can confirm by opening your browser DevTools and watching the network tab: no requests are made.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. Copyright 0xelitesystem 2026.
