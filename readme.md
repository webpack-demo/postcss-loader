# postcss-loader

```bash
$ npm install postcss-loader autoprefixer -D
```

以 autoprefixer 为例，先对 css 文件配置 postcss-loader

然后新建 postcss.config.js 文件，在这里指定要用的 postcss 插件

autoprefixer 要作用还需要指定需要兼容的浏览器，新建 .browserslistrc 文件

---

注意 postcss-loader 是作用在 css 上的 loader，它的核心是将 css 转成 css ast，然后用 postcss plugin 对其做一系列转换，再从 ast 转成 css 样式

