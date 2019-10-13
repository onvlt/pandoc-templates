# Pandoc context templates

Pandoc templates I use for producing nice-looking PDF writings.

## Prerequisities

- TeX distribution
- Fonts: IMB Plex Serif, IMB Plex Sans, IMB Plex Mono

## Installation

See [Pandoc documentation](https://pandoc.org/MANUAL.html#templates) to see how to install and use templates.

1. Download template of choice from `src` directory.
2. Put template into `DATA_DIR/templates` (eg. `~/.pandoc/templates`)

## Usage

```sh
pandoc text.md -o text.pdf -t context --template=custom
```
