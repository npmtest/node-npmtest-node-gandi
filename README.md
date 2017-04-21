# npmtest-node-gandi

#### basic test coverage for  [node-gandi (v2.0.1)](https://github.com/Pegase745/node-gandi#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-gandi.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-gandi) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-gandi.svg)](https://travis-ci.org/npmtest/node-npmtest-node-gandi)

#### Node.js client for Gandi.net XML-RPC API.

[![NPM](https://nodei.co/npm/node-gandi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-gandi)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-gandi/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gandi/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-gandi/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-gandi/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-gandi/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-gandi/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-gandi/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-gandi/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-gandi/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gandi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-gandi/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-gandi/build/test-report.html](https://npmtest.github.io/node-npmtest-node-gandi/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-gandi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-gandi/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-gandi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-gandi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gandi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gandi/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-gandi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-gandi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-gandi",
    "version": "2.0.1",
    "description": "Node.js client for Gandi.net XML-RPC API.",
    "main": "./src/gandi.js",
    "scripts": {
        "lint": "jshint src && jscs src",
        "test": "mocha tests --recursive"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Pegase745/node-gandi.git"
    },
    "keywords": [
        "gandi",
        "xmlrpc",
        "api",
        "client"
    ],
    "author": "Michel Nemnom",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Pegase745/node-gandi/issues"
    },
    "homepage": "https://github.com/Pegase745/node-gandi#readme",
    "devDependencies": {
        "jscs": "2.0.x",
        "jshint": "2.8.x",
        "lodash": "3.10.x",
        "mocha": "2.2.x"
    },
    "dependencies": {
        "xmlrpc": "1.3.x"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
