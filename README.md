# @nomadland/____

[![npm version](https://badgen.net/npm/v/@nomadland/____)](https://npm.im/@nomadland/____) 

Shipped a standard `npm publish` workflow with one click.

## Motivation

As a maintainer for a large number of NPM packages, it will be very cumbersome if you manually input the semantic version, generate changelog, git and npm tag etc., this tooling is to help you do all these things with one click.

## Features

- Semantic version selection.
- Create git tag.
- Create remote git tag.
- Create npm tag.
- Generate or update `CHANGELOG.md`

## Install

```bash
npm i @nomadland/____ -g      # Global installation
npm i @nomadland/____ -D      # Local installation
```

## Usage

- Create a one-click release flow:

```bash
publish
```

- Display help:

```bash
Usage:
  $ publish

Commands:
    Shipped a standard `npm publish` workflow with one click.

Options:
  --depcost      Generate or update `DEPCOST.md`, defaults to `false`
  --push         Execute git push & tag push to remote git origin, defaults to `true`
  -h, --help     Display this message
  -v, --version  Display version number
```

## Credits

`@nomadland/____` wouldn't exist without the inspirations from following projects:

- [conventional-changelog-cli](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-cli)


## License

MIT &copy; [ULIVZ](https://github.com/sponsors/ulivz)