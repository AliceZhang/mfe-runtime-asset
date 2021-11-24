# Prettier Config

My personal shareable prettier configuration.

## Install

```bash
npm i --save-dev @waldronmatt/prettier-config
```

## Usage

**`prettier.config.js`**

```js
module.exports = "@waldronmatt/prettier-config";
```

## Extending

**`prettier.config.js`**

```js
module.exports = {
  ...require("@waldronmatt/prettier-config"),
  semi: false,
};
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT
