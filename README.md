# Fruit palettes

A small single-file HTML tool that turns a cut-open fruit into an app color palette.

Tap a fruit (orange, kiwi, pomegranate or dragon fruit) and the tool pulls five colors from its skin, flesh, seeds and pith. A mock phone screen shows the palette in use, with a light and dark toggle that derives the colors for each mode. Text contrast is checked against WCAG AA, anything that fails is flagged, and a one-tap fix nudges the color. Hex values and CSS variables can be copied.

## Status

This repo is the open-source home for the tool, and it is early: the working version currently lives in the portfolio site's source, under `demo/fruit-palettes/` in [holroydchase-afk/holroydchase-afk.github.io](https://github.com/holroydchase-afk/holroydchase-afk.github.io). Moving the file here is the next step. It has no automated tests yet.

## Try it

Open the demo from [chaseholroyd.com](https://chaseholroyd.com). It is one HTML file with no libraries and no outside hosts, so it also runs by opening the file in a browser.

## Contributing

Issues and small pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE)

## How this is built

Built with Claude Code (AI-assisted code, tests and docs). The maintainer directs the work and decides what ships. 
