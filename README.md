# npmtest-basic-auth

#### basic test coverage for  [basic-auth (v1.1.0)](https://github.com/jshttp/basic-auth)  [![npm package](https://img.shields.io/npm/v/npmtest-basic-auth.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-basic-auth) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-basic-auth.svg)](https://travis-ci.org/npmtest/node-npmtest-basic-auth)

#### node.js basic auth parser

[![NPM](https://nodei.co/npm/basic-auth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/basic-auth)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-basic-auth/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-basic-auth/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-basic-auth/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-basic-auth/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-basic-auth/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-basic-auth/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-basic-auth/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-basic-auth/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-basic-auth/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-basic-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-basic-auth/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-basic-auth/build/test-report.html](https://npmtest.github.io/node-npmtest-basic-auth/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-basic-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-basic-auth/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-basic-auth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-basic-auth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-basic-auth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-basic-auth/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-basic-auth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-basic-auth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/basic-auth/issues"
    },
    "dependencies": {},
    "description": "node.js basic auth parser",
    "devDependencies": {
        "eslint": "3.10.2",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.0",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "45221ee429f7ee1e5035be3f51533f1cdfd29884",
        "tarball": "https://registry.npmjs.org/basic-auth/-/basic-auth-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "gitHead": "5a0fcd9f4dbf72e2a105d4e815987d3492925875",
    "homepage": "https://github.com/jshttp/basic-auth",
    "keywords": [
        "basic",
        "auth",
        "authorization",
        "basicauth"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jonathanong"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "basic-auth",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/basic-auth.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --check-leaks --reporter spec --bail",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
