# Resolve

|本期版本| 上期版本
|:---:|:---:
`Tue Dec 10 18:58:32 CST 2024` | -

```javascript
const path = require('path');
const resolve = dir => path.resolve(__dirname, dir);

module.exports = {
  resolve: {
    alias: {
        '@': resolve('src')// 这样配置后 @ 可以指向 src 目录
    }
  }
};

```

## Ref

* <https://webpack.js.org/configuration/resolve/>
* <https://www.cnblogs.com/Jimc/p/10282969.html>