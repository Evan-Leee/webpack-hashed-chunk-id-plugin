# webpack-hashed-chunk-id-plugin

Designate hashed chunk path as the chunk id

## Install

```shell
$ npm i webpack-hashed-chunk-id-plugin --save
```

## Usage

```js
const hashedChunkIdPlugin = require('webpack-hashed-chunk-id-plugin')

webpackConfig = {
  plugins: [
    new hashedChunkIdPlugin()
  ]
}
```

You can specify the hash length you want (defualt 4):

```js
new hashedChunkIdPlugin({
  length: 10
})
```

## Author

[daixinye](https://github.com/daixinye)
