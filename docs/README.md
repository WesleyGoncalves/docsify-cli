# docsify-cli

[![Build Status master branch](https://img.shields.io/travis/QingWei-Li/docsify-cli/master.svg?style=flat-square)](https://travis-ci.org/QingWei-Li/docsify-cli)
[![License](https://img.shields.io/github/license/QingWei-Li/docsify-cli.svg?style=flat-square)](https://github.com/QingWei-Li/docsify-cli/blob/master/LICENSE)
[![Github tag](https://img.shields.io/github/tag/QingWei-Li/docsify-cli.svg?style=flat-square)](https://github.com/QingWei-Li/docsify-cli/tags)
[![npm version](https://img.shields.io/npm/v/docsify-cli.svg?style=flat-square)](https://www.npmjs.com/package/docsify-cli)
[![npm total downloads](https://img.shields.io/npm/dt/docsify-cli.svg?style=flat-square)](https://www.npmjs.com/package/docsify-cli)
[![npm total monthly](https://img.shields.io/npm/dm/docsify-cli.svg?style=flat-square)](https://www.npmjs.com/package/docsify-cli)

> 🖌 docsify cli - A magical documentation generator.

## Links

* [docsify](https://github.com/docsifyjs/docsify)

## Screencast

![Screencast](https://raw.githubusercontent.com/docsifyjs/docsify-cli/master/media/screencast.gif)

> Running a server on `localhost` with live-reload.

## Installation

Install `docsify-cli` via `npm` or `yarn` globally.

```shell
npm i docsify-cli -g
# yarn global add docsify-cli
```

## Usage

### `init` command

Use `init` to generate your docs.

```shell
docsify init <path> [--local false] [--theme vue] [--sidebar false] [--navbar false] [--coverpage false]

# docsify i <path> [--local false] [--theme vue] [--sidebar false] [--navbar false] [--coverpage false]
```

`<path>` defaults to the current directory. Use relative paths like `./docs` (or `docs`).

* `--local` option:
  * Shorthand: `-l`
  * Type: boolean
  * Default: `false`
  * Description: Copy `docsify` files to the docs path, defaults to `false` using `jsDelivr` as the content delivery network (CDN). To explicitly set this option to `false` use `--no-local`.
* `--theme` option:
  * Shorthand: `-t`
  * Type: string
  * Default: `vue`
  * Description: Choose a theme, defaults to `vue`, other choices are `buble`, `dark` and `pure`.
* `--sidebar` option:
  * Shorthand: `-s`
  * Type: boolean
  * Default: `false`
  * Description: Include sidebar when generating a new doc, defaults to `false`.
* `--navbar` option:
  * Shorthand: `-n`
  * Type: boolean
  * Default: `false`
  * Description: Include navbar when generating a new doc, defaults to `false`.
* `--coverpage` option:
  * Shorthand: `-c`
  * Type: boolean
  * Default: `false`
  * Description: Include coverpage when generating a new doc, defaults to `false`.

### `serve` command

Run a server on `localhost` with livereload.

```shell
docsify serve <path> [--open false] [--port 3000]

# docsify s <path> [--open false] [--port 3000]
```

* `--open` option:
  * Shorthand: `-o`
  * Type: boolean
  * Default: `false`
  * Description: Open the docs in the default browser, defaults to `false`. To explicitly set this option to `false` use `--no-open`.
* `--port` option:
  * Shorthand: `-p`
  * Type: number
  * Default: `3000`
  * Description: Choose a listen port, defaults to `3000`.

## License

MIT
