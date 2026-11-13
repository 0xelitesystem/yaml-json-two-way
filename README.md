# YAML to JSON

A single file, offline, browser based converter that turns YAML into JSON and JSON back into YAML, live as you type.

**Live demo:** https://0xelitesystem.github.io/yaml-to-json/

## Use

Paste or type into the left pane and the converted result appears in the right pane instantly. Use the toggle to pick the direction (YAML to JSON or JSON to YAML). Each pane has a copy button. If the input is invalid, a clear error message replaces the output until you fix it.

## Why this exists

Most YAML and JSON converters are web services that send your data to a server, or heavy npm packages you have to install. Config files often hold secrets, tokens, and internal hostnames, so pasting them into a random website is a bad habit. This tool is one HTML file with no build step, no dependencies, and no network calls, so you can keep it on a USB stick or a private intranet and trust that nothing leaves the page.

## Privacy

Everything runs locally in your browser. There are no analytics, no cookies, no external scripts, no fonts loaded from a CDN, and no requests of any kind. Your input never leaves your machine. You can confirm this by opening the network tab and watching it stay empty, or by loading the page with your connection turned off.

## Run locally

Open `index.html` in any modern browser. Double click the file, or drag it onto a browser window. That is the whole setup. No server, no install, no internet connection required.

## Build

There is no build. The project is intentionally a single self contained `index.html` with inline CSS and JavaScript. To deploy it, copy that one file to any static host (for example GitHub Pages) and you are done.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. See the [LICENSE](LICENSE) file. Copyright (c) 2026 RBL Industries LLC.
