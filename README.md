# npmtest-koa-static

#### basic test coverage for  [koa-static (v3.0.0)](https://github.com/koajs/static#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-static.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-static) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-static.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-static)

#### Static file serving middleware for koa

[![NPM](https://nodei.co/npm/koa-static.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-static)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-static/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-static/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-static/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-static/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-static/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-koa-static/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-koa-static/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-static/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-static/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-static/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-static/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-static/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-static/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-static/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-static/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-static/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-static/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-static/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-static/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-static/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-static/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-static/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-static/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/koajs/static/issues"
    },
    "dependencies": {
        "debug": "*",
        "koa-send": "^3.2.0"
    },
    "description": "Static file serving middleware for koa",
    "devDependencies": {
        "istanbul": "0",
        "koa": "2",
        "mocha": "2",
        "supertest": "1"
    },
    "directories": {},
    "dist": {
        "shasum": "40442233d2c0b35c225e450199c10bf8a539e416",
        "tarball": "https://registry.npmjs.org/koa-static/-/koa-static-3.0.0.tgz"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "855a20c94035f6009ff9601615e05228b6a9d20e",
    "homepage": "https://github.com/koajs/static#readme",
    "keywords": [
        "koa",
        "middleware",
        "file",
        "static",
        "sendfile"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "aheckmann"
        },
        {
            "name": "coderhaoxin"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "eivifj"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "tejasmanohar"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "koa-static",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/static.git"
    },
    "scripts": {
        "test": "mocha --harmony --reporter spec",
        "test-cov": "node --harmony ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha",
        "test-travis": "node --harmony ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
