# npmtest-svg-captcha

#### basic test coverage for  [svg-captcha (v1.3.4)](https://github.com/steambap/svg-captcha#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-svg-captcha.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg-captcha) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg-captcha.svg)](https://travis-ci.org/npmtest/node-npmtest-svg-captcha)

#### generate svg captcha in node.js or express.js

[![NPM](https://nodei.co/npm/svg-captcha.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg-captcha)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg-captcha/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-captcha/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg-captcha/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg-captcha/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg-captcha/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg-captcha/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg-captcha/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg-captcha/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg-captcha/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-captcha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg-captcha/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg-captcha/build/test-report.html](https://npmtest.github.io/node-npmtest-svg-captcha/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg-captcha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg-captcha/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg-captcha/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg-captcha/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg-captcha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg-captcha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "svg-captcha",
    "version": "1.3.4",
    "description": "generate svg captcha in node.js or express.js",
    "main": "index.js",
    "scripts": {
        "test": "mocha test/test.js",
        "lint": "xo",
        "test:visual": "node test/visual.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/steambap/svg-captcha.git"
    },
    "keywords": [
        "captcha",
        "svg",
        "node captcha",
        "captcha generator",
        "captcha alternative"
    ],
    "author": {
        "name": "Weilin Shi",
        "url": "weilinshi.org"
    },
    "engines": {
        "node": ">=4.x"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/steambap/svg-captcha/issues"
    },
    "homepage": "https://github.com/steambap/svg-captcha#readme",
    "dependencies": {
        "opentype.js": "^0.6.9"
    },
    "devDependencies": {
        "fs-extra": "^2.1.2",
        "mocha": "^3.2.0",
        "xo": "^0.18.1"
    },
    "xo": {
        "esnext": true,
        "envs": [
            "mocha"
        ]
    },
    "typings": "index.d.ts",
    "files": [
        "fonts/*",
        "lib/*",
        "index.d.ts",
        "*.md"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
