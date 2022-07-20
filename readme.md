
# Start
```
npm init -y
npm install webpack webpack-cli --save-dev
```

## config webpack
```js
const path = require('path');

module.exports = {
    entry: './src/index.ts',
    output: {
        filename: 'main.js',
        path: path.resolve(__dirname, 'dist'),
    },
};
```

