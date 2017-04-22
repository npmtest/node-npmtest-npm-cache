# npmtest-npm-cache

#### basic test coverage for  [npm-cache (v0.6.5)](https://github.com/swarajban/npm-cache)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-cache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-cache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-cache.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-cache)

#### cache dependency manager installs to local machine

[![NPM](https://nodei.co/npm/npm-cache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-cache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-cache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-cache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-cache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-cache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-cache/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-cache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-cache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-cache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-cache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-cache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-cache/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-cache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-cache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-cache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-cache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-cache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-cache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-cache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npm-cache",
    "version": "0.6.5",
    "description": "cache dependency manager installs to local machine",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/swarajban/npm-cache.git"
    },
    "keywords": [
        "npm",
        "cache",
        "install",
        "bower",
        "jspm",
        "composer",
        "local"
    ],
    "author": "swaraj",
    "contributors": [
        {
            "name": "Aaron Nordyke"
        }
    ],
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/swarajban/npm-cache/issues"
    },
    "homepage": "https://github.com/swarajban/npm-cache",
    "dependencies": {
        "async": "1.5.0",
        "fs-extra": "^0.26.2",
        "fstream": "^1.0.8",
        "lodash": "3.10.1",
        "md5": "2.0.0",
        "nomnom": "1.8.1",
        "rimraf": "^2.5.4",
        "shelljs": "0.5.3",
        "tar-fs": "1.14.0",
        "tmp": "^0.0.28",
        "which": "^1.2.0"
    },
    "preferGlobal": true,
    "bin": {
        "npm-cache": "index.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
