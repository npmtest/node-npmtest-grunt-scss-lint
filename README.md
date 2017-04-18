# npmtest-grunt-scss-lint

test coverage for  [grunt-scss-lint (v0.5.0)](https://github.com/ahmednuaman/grunt-scss-lint)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-scss-lint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-scss-lint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-scss-lint.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-scss-lint)
#### Validate `.scss` files with `scss-lint`.

[![NPM](https://nodei.co/npm/grunt-scss-lint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-scss-lint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-scss-lint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-scss-lint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-scss-lint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-scss-lint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-scss-lint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-scss-lint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-scss-lint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-scss-lint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ahmed Nuaman",
        "url": "http://ahmednuaman.com/"
    },
    "bugs": {
        "url": "https://github.com/ahmednuaman/grunt-scss-lint/issues"
    },
    "contributors": [
        {
            "name": "Ahmed Nuaman",
            "url": "http://ahmednuaman.com/"
        },
        {
            "name": "Thomas P. Horton",
            "url": "http://thomasphorton.com/"
        },
        {
            "name": "Thomas Bremer",
            "url": "https://github.com/tbremer/"
        },
        {
            "name": "Nikolaos Georgiou",
            "url": "http://ngeor.net/"
        }
    ],
    "dependencies": {
        "chalk": "^1.1.3",
        "lodash": "^4.12.0",
        "which": "^1.2.8",
        "xmlbuilder": "^8.2.2"
    },
    "description": "Validate '.scss' files with 'scss-lint'.",
    "devDependencies": {
        "codeclimate-test-reporter": "0.3.1",
        "expect.js": "^0.3.1",
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-jscs": "^2.8.0",
        "grunt-mocha-istanbul": "^4.0.2",
        "istanbul": "^0.4.3",
        "mocha": "^2.4.5",
        "proxyquire": "^1.7.9",
        "sinon": "^1.17.4"
    },
    "directories": {},
    "dist": {
        "shasum": "9b9823f8074f334650ff831f551a1ecf5b08a215",
        "tarball": "https://registry.npmjs.org/grunt-scss-lint/-/grunt-scss-lint-0.5.0.tgz"
    },
    "gitHead": "c7ed6adff4e1f3f115532f7d9f560b5f7a803e0d",
    "homepage": "https://github.com/ahmednuaman/grunt-scss-lint",
    "keywords": [
        "gruntplugin",
        "scss",
        "lint",
        "scss-lint",
        "junit"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/ahmednuaman/grunt-scss-lint/blob/master/LICENSE-MIT"
        }
    ],
    "maintainers": [
        {
            "name": "ahmednuaman"
        }
    ],
    "name": "grunt-scss-lint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ahmednuaman/grunt-scss-lint.git"
    },
    "scripts": {
        "codeclimate": "CODECLIMATE_REPO_TOKEN=dbf49c8de102d946c65f8195714e9d58591833be9975cd897bae0f0908c05235 codeclimate < coverage/lcov.info",
        "test": "bundle && grunt test"
    },
    "version": "0.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
