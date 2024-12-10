# postcss-loader

|本期版本|上期版本
|:---:|:---:
`Tue Dec 10 20:06:13 CST 2024` | `Sat May 21 09:34:58 CST 2022`

## [883--day51_webpack打包各种资源-loader-插件_04_(理解)webpack中postcss-loader的](https://github.com/nanana-100/coderwhy/tree/main/s05/day51/0883)


```bash
npm install --save-dev postcss-preset-env
# npm install --save-dev autoprefixer
```

---

```bash
npm install --save-dev postcss-loader postcss
```


* `postcss-loader` 执行顺序必须保证在 `css-loader` 之前，建议还是放在 `less` 或者 `sass` 等预处理器之后更好。
* 即 `loader` 顺序： `less-loader` -> `postcss-loader` -> `css-loader` -> `style-loader` 或者 `MiniCssExtractPlugin.loader`

## Ref

* <https://webpack.js.org/loaders/postcss-loader/>
* <https://time.geekbang.org/course/detail/100028901-99020>
* [13 分钟掌握 PostCSS](https://www.bilibili.com/video/BV1Pd4y1S7Mp/)
* <https://postcss.org/>
* <https://github.com/csstools/postcss-plugins/tree/main/plugin-packs/postcss-preset-env>