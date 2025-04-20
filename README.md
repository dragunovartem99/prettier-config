# Personal Prettier Config

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
