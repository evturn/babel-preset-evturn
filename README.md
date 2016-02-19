[![npm version](https://badge.fury.io/js/babel-preset-evturn.svg)](https://badge.fury.io/js/babel-preset-evturn)

### Install

```bash
npm install --save-dev babel-preset-evturn
```

### Configure babel via .babelrc
```json
{
  "presets": ["evturn"]
}
```

### Plugins in this preset include:

 * [babel-plugin-array-includes](https://www.npmjs.com/package/babel-plugin-array-includes)
 * [babel-plugin-syntax-class-properties](https://www.npmjs.com/package/babel-plugin-syntax-class-properties)
 * [babel-plugin-syntax-decorators](https://www.npmjs.com/package/babel-plugin-syntax-decorators)
 * [babel-plugin-syntax-object-rest-spread](https://www.npmjs.com/package/babel-plugin-syntax-object-rest-spread)
 * [babel-plugin-transform-class-properties](https://www.npmjs.com/package/babel-plugin-transform-class-properties)
 * [babel-plugin-transform-decorators-legacy](https://www.npmjs.com/package/babel-plugin-transform-decorators-legacy) (for my fallen homies)
 * [babel-plugin-transform-object-assign](https://www.npmjs.com/package/babel-plugin-transform-object-assign)
 * [babel-plugin-transform-object-rest-spread](https://www.npmjs.com/package/babel-plugin-transform-object-rest-spread)

Usage with Babel 6

```bash
npm install --save-dev babel-core babel-preset-evturn
```

```javascript
// Loaded babel in a separate file and require in your entry file
require('babel-core/register')({});
require('./your-app');
```

Note: depending on your babel setup you may be required to run in strict-mode by placing `'use strict'` at the top of your files.