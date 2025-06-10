# Personal Prettier Config

<a href="https://github.com/dragunovartem99/prettier-config/blob/main/index.js" target="_blank"><img alt="Static Badge" src="https://img.shields.io/badge/View_Configuration-red"></a>
<img alt="NPM Downloads" src="https://img.shields.io/npm/d18m/@dragunovartem99/prettier-config?color=blue">
<img alt="npm bundle size" src="https://img.shields.io/bundlephobia/min/@dragunovartem99/prettier-config?color=blue">
<img alt="NPM Version" src="https://img.shields.io/npm/v/@dragunovartem99/prettier-config?color=orange">

This configuration uses **explicit** style, to maintain readability and minimize mistakes, for example:

- Semicolons
- Arrow function parentheses
- Reasonable print width (100 chars)
- Double quotes (some kind of C "vibe")

And it uses tabs (or 4 spaces in formats like YAML)

## Installation

```shell
npm install --save-dev @dragunovartem99/prettier-config
```

## Usage

1. Add the configuration to your project's `package.json`:

```json
{
    "scripts": {
        "format": "prettier . --write",
        "format:check": "prettier . --check"
    },
    "prettier": "@dragunovartem99/prettier-config"
}
```

2. Run the formatter:

```shell
npm run format
```

Or check formatting without modifications:

```shell
npm run format:check
```

## Creating your own configuration

For creating similar configurations, see:

- [Prettier's configuration sharing guide](https://prettier.io/docs/en/sharing-configurations)
- [npm's documentation on scoped packages](https://docs.npmjs.com/creating-and-publishing-scoped-public-packages)
