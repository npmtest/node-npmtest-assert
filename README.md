# npmtest-assert

#### basic test coverage for  [assert (v1.4.1)](https://github.com/defunctzombie/commonjs-assert)  [![npm package](https://img.shields.io/npm/v/npmtest-assert.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-assert) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-assert.svg)](https://travis-ci.org/npmtest/node-npmtest-assert)

#### commonjs assert - node.js api compatible

[![NPM](https://nodei.co/npm/assert.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/assert)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-assert/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-assert/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-assert/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-assert/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-assert/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-assert/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-assert/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-assert/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-assert/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-assert/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-assert/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-assert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-assert/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-assert/build/test-report.html](https://npmtest.github.io/node-npmtest-assert/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-assert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-assert/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-assert/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-assert/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-assert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-assert/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-assert/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-assert/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/defunctzombie/commonjs-assert/issues"
    },
    "dependencies": {
        "util": "0.10.3"
    },
    "description": "commonjs assert - node.js api compatible",
    "devDependencies": {
        "mocha": "~1.21.4",
        "zuul": "~3.10.0",
        "zuul-ngrok": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "99912d591836b5a6f5b345c0f07eefc08fc65d91",
        "tarball": "https://registry.npmjs.org/assert/-/assert-1.4.1.tgz"
    },
    "gitHead": "ea25d53a51201cf268681c5ec37f7d51b2d82884",
    "homepage": "https://github.com/defunctzombie/commonjs-assert",
    "keywords": [
        "assert"
    ],
    "license": "MIT",
    "main": "./assert.js",
    "maintainers": [
        {
            "name": "coolaj86"
        },
        {
            "name": "cwmma"
        },
        {
            "name": "defunctzombie"
        }
    ],
    "name": "assert",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/defunctzombie/commonjs-assert.git"
    },
    "scripts": {
        "browser-local": "zuul --no-coverage --local 8000 -- test.js",
        "test": "npm run test-node && npm run test-browser",
        "test-browser": "zuul -- test.js",
        "test-native": "TEST_NATIVE=true mocha --ui qunit test.js",
        "test-node": "mocha --ui qunit test.js"
    },
    "version": "1.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
