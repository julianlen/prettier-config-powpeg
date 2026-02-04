# prettier-config-powpeg

A shareable Prettier configuration for PowPeg projects.

## Installation

Install this package as a dev dependency:

```
npm install --save-dev prettier-config-powpeg
```

## Usage

Add the following to your `package.json`:

```
"prettier": "prettier-config-powpeg"
```

Or create a `.prettierrc.json` file:

```
powpegPrettierConfig = require('prettier-config-powpeg');

module.exports = {
    ...powpegPrettierConfig,
};
```

## Extending or Overriding

If you need to override specific Prettier options, you can do so in your own config file. See the [Prettier documentation](https://prettier.io/docs/en/configuration.html) for more details.
