## How to create something like this?

- https://prettier.io/docs/en/sharing-configurations
- https://docs.npmjs.com/creating-and-publishing-scoped-public-packages

## Basic usage

1. Install via npm

```shell
npm install --save-dev @dragunovatem99/prettier-config
```

2. Modify `package.json` in `<your-next-project>`

```json
{
    "name": "<your-next-project>",
    "version": "1.0.0",
    "prettier": "@dragunovartem99/prettier-config"
}
```

3. Run it by using

```shell
npx prettier . --write
```
