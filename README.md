# Cod3Rocket eslint config

Eslint config use by Cod3Rocket. It is based on the eslint config [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb) with little changes.

## Usage

### Install peer dependencies

```bash
pnpm add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-import-helpers eslint-plugin-prettier prettier typescript
```

with use with react.

```bash
pnpm add -D eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks
```

and install `eslint-config-cod3rocket`

```bash
pnpm add -D eslint-config-cod3rocket
```

## Configuration

in our eslint config file

```json
{
  "extends": ["cod3rocket"],
}
```

## License

[MIT](./LICENSE)
