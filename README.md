# nextjs-demo

Use Next.js with Egg.js by egg-nextjs

[![build status][travis-image]][travis-url]
[![codecov](https://codecov.io/gh/h1bomb/egg-nextjs-demo/branch/master/graph/badge.svg)](https://codecov.io/gh/h1bomb/egg-nextjs-demo)


[travis-image]: https://travis-ci.org/h1bomb/egg-nextjs-demo.svg?branch=master
[travis-url]: https://travis-ci.org/h1bomb/egg-nextjs-demo


## QuickStart

```javascript
// config/plugin.js
exports.nextjs = {
    enable: true,
    package: 'egg-nextjs',
};

```

see [egg docs][egg] for more detail.

### Development

```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

### Deploy

```bash
$ npm start
$ npm stop
```

### npm scripts

- Use `npm run lint` to check code style.
- Use `npm test` to run unit test.
- Use `npm run autod` to auto detect dependencies upgrade, see [autod](https://www.npmjs.com/package/autod) for more detail.


[egg]: https://eggjs.org
