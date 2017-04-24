# npmtest-intercom-client

#### basic test coverage for  [intercom-client (v2.8.7)](https://github.com/intercom/intercom-node)  [![npm package](https://img.shields.io/npm/v/npmtest-intercom-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-intercom-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-intercom-client.svg)](https://travis-ci.org/npmtest/node-npmtest-intercom-client)

#### Official Node bindings to the Intercom API

[![NPM](https://nodei.co/npm/intercom-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/intercom-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-intercom-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-intercom-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-intercom-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-intercom-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-intercom-client/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-intercom-client/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-intercom-client/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-intercom-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-intercom-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-intercom-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-intercom-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-intercom-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-intercom-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-intercom-client/build/test-report.html](https://npmtest.github.io/node-npmtest-intercom-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-intercom-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-intercom-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-intercom-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-intercom-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-intercom-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-intercom-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-intercom-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-intercom-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bob Long"
    },
    "bugs": {
        "url": "https://github.com/intercom/intercom-node/issues"
    },
    "bugs:": "https://github.com/intercom/intercom-node/issues",
    "dependencies": {
        "bluebird": "^3.3.4",
        "unirest": "^0.5.1"
    },
    "description": "Official Node bindings to the Intercom API",
    "devDependencies": {
        "babel-core": "^6.7.4",
        "babel-eslint": "^5.0.0",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-stage-1": "^6.5.0",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-eslint": "^0.15.0",
        "gulp-exclude-gitignore": "^1.0.0",
        "gulp-istanbul": "^0.10.3",
        "gulp-mocha": "^2.0.0",
        "gulp-nsp": "^2.3.1",
        "gulp-plumber": "^1.1.0",
        "nock": "7.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "078fc6de68a63c6399474eb4864b96552615d5bb",
        "tarball": "https://registry.npmjs.org/intercom-client/-/intercom-client-2.8.7.tgz"
    },
    "engines": {
        "node": ">= v0.10.0"
    },
    "files": [
        "dist"
    ],
    "gitHead": "232132e576667e9f2da79b07ee0c531991b9e2ca",
    "homepage": "https://github.com/intercom/intercom-node",
    "keywords": [
        "intercom",
        "api"
    ],
    "license": "Apache-2.0",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "bobintercom"
        },
        {
            "name": "skaelv"
        }
    ],
    "name": "intercom-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/intercom/intercom-node.git"
    },
    "scripts": {
        "prepublish": "gulp prepublish",
        "test": "gulp"
    },
    "version": "2.8.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
