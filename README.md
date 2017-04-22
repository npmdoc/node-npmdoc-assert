# npmdoc-assert

#### api documentation for  [assert (v1.4.1)](https://github.com/defunctzombie/commonjs-assert)  [![npm package](https://img.shields.io/npm/v/npmdoc-assert.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-assert) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-assert.svg)](https://travis-ci.org/npmdoc/node-npmdoc-assert)

#### commonjs assert - node.js api compatible

[![NPM](https://nodei.co/npm/assert.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/assert)

- [https://npmdoc.github.io/node-npmdoc-assert/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-assert/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-assert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-assert/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-assert/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-assert/build/screenCapture.npmPackageDependencyTree.svg)



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
