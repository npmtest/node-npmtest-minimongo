# npmtest-minimongo

#### test coverage for  [minimongo (v4.5.0)](https://github.com/mWater/minimongo)  [![npm package](https://img.shields.io/npm/v/npmtest-minimongo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-minimongo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-minimongo.svg)](https://travis-ci.org/npmtest/node-npmtest-minimongo)

#### Client-side mongo database with server sync over http

[![NPM](https://nodei.co/npm/minimongo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/minimongo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-minimongo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-minimongo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-minimongo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-minimongo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-minimongo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-minimongo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-minimongo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-minimongo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-minimongo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-minimongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-minimongo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-minimongo/build/test-report.html](https://npmtest.github.io/node-npmtest-minimongo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-minimongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-minimongo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-minimongo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-minimongo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-minimongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-minimongo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-minimongo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-minimongo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Clayton Grassick"
    },
    "bugs": {
        "url": "https://github.com/mWater/minimongo/issues"
    },
    "dependencies": {
        "async": "^1.4.2",
        "bowser": "^0.7.1",
        "idb-wrapper": "^1.4.1",
        "jquery": "~2.1.0",
        "lodash": "^3.10.1"
    },
    "description": "Client-side mongo database with server sync over http",
    "devDependencies": {
        "browserify": "^3.29.1",
        "chai": "~1.9.0",
        "coffee-script": "~1.6.3",
        "coffeeify": "~0.6.0",
        "glob": "^3.2.9",
        "gulp": "^3.8.11",
        "gulp-coffee": "^1.4.2",
        "gulp-rename": "^1.2.0",
        "gulp-uglify": "^0.3.1",
        "gulp-util": "^2.2.14",
        "karma": "^0.13.10",
        "karma-browserify": "^4.3.0",
        "karma-chrome-launcher": "^0.2.0",
        "karma-mocha": "^0.2.0",
        "lolex": "^1.5.0",
        "sinon": "~1.8.2",
        "testem": "~0.6.7",
        "vinyl-buffer": "0.0.0",
        "vinyl-source-stream": "^0.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "602467758dcaa7ebccf6bbba0a81887740aae278",
        "tarball": "https://registry.npmjs.org/minimongo/-/minimongo-4.5.0.tgz"
    },
    "gitHead": "24d9d8677e489679c3e87b053f589a16083ea9a9",
    "homepage": "https://github.com/mWater/minimongo",
    "keywords": [
        "mongodb",
        "mongo",
        "minimongo",
        "IndexedDb",
        "WebSQL",
        "storage"
    ],
    "license": "LGPLv3",
    "main": "index.js",
    "maintainers": [
        {
            "name": "grassick"
        }
    ],
    "name": "minimongo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mWater/minimongo.git"
    },
    "scripts": {
        "prepublish": "gulp",
        "test": "testem ci"
    },
    "version": "4.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
