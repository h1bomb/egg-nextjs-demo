# nextjs-demo

使用 egg-nextjs插件，集成Next.js

[![build status][travis-image]][travis-url]
[![codecov](https://codecov.io/gh/h1bomb/egg-nextjs-demo/branch/master/graph/badge.svg)](https://codecov.io/gh/h1bomb/egg-nextjs-demo)


[travis-image]: https://travis-ci.org/h1bomb/egg-nextjs-demo.svg?branch=master
[travis-url]: https://travis-ci.org/h1bomb/egg-nextjs-demo
## 快速入门

```javascript
// config/plugin.js
exports.nextjs = {
    enable: true,
    package: 'egg-nextjs',
};

```


如需进一步了解，参见 [egg 文档][egg]。

### 本地开发

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

### 部署

```bash
$ npm start
$ npm stop
```

### 单元测试

- [egg-bin] 内置了 [mocha], [thunk-mocha], [power-assert], [istanbul] 等框架，让你可以专注于写单元测试，无需理会配套工具。
- 断言库非常推荐使用 [power-assert]。
- 具体参见 [egg 文档 - 单元测试](https://eggjs.org/zh-cn/core/unittest)。

### 内置指令

- 使用 `npm run lint` 来做代码风格检查。
- 使用 `npm test` 来执行单元测试。
- 使用 `npm run autod` 来自动检测依赖更新，详细参见 [autod](https://www.npmjs.com/package/autod) 。


[egg]: https://eggjs.org
