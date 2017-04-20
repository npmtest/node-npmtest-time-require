# npmtest-time-require

#### basic test coverage for  [time-require (v0.1.2)](https://github.com/jaguard/time-require)  [![npm package](https://img.shields.io/npm/v/npmtest-time-require.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-time-require) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-time-require.svg)](https://travis-ci.org/npmtest/node-npmtest-time-require)

#### Displays the execution time for Node.js modules loading; inspired by @sindresorhus 'time-grunt'

[![NPM](https://nodei.co/npm/time-require.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/time-require)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-time-require/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-time-require/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-time-require/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-time-require/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-time-require/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-time-require/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-time-require/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-time-require/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-time-require/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-time-require/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-time-require/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-time-require/build/test-report.html](https://npmtest.github.io/node-npmtest-time-require/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-time-require/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-time-require/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-time-require/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-time-require/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-time-require/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-time-require/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-time-require/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-time-require/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jaguard OSS",
        "url": "http://oss.jaguard.com"
    },
    "bugs": {
        "url": "https://github.com/jaguard/time-require/issues"
    },
    "dependencies": {
        "chalk": "^0.4.0",
        "date-time": "^0.1.1",
        "pretty-ms": "^0.2.1",
        "text-table": "^0.2.0"
    },
    "description": "Displays the execution time for Node.js modules loading; inspired by @sindresorhus 'time-grunt'",
    "devDependencies": {
        "gulp": "~3.6.0",
        "gulp-cached": "~0.0.3",
        "gulp-clean": "~0.2.4",
        "gulp-docco": "~0.0.4",
        "gulp-if": "~1.0.0",
        "gulp-jasmine": "~0.2.0",
        "gulp-jscs": "~0.4.0",
        "gulp-jsdoc": "~0.1.4",
        "gulp-jshint": "~1.5.2",
        "gulp-jsonlint": "~0.0.3",
        "gulp-load-plugins": "~0.5.0",
        "gulp-markdown": "~0.1.2",
        "gulp-markdown-pdf": "~0.2.0",
        "gulp-match": "~0.0.2",
        "gulp-notify": "~1.2.5",
        "gulp-util": "~2.2.14",
        "jshint-stylish": "~0.1.5",
        "run-sequence": "~0.3.6"
    },
    "directories": {},
    "dist": {
        "shasum": "f9e12cb370fc2605e11404582ba54ef5ca2b2d98",
        "tarball": "https://registry.npmjs.org/time-require/-/time-require-0.1.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "homepage": "https://github.com/jaguard/time-require",
    "keywords": [
        "require",
        "measure",
        "time",
        "profile"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/jaguard/time-require/raw/master/LICENSE"
        }
    ],
    "main": "src/timeRequire.js",
    "maintainers": [
        {
            "name": "jaguard"
        }
    ],
    "name": "time-require",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jaguard/time-require.git"
    },
    "scripts": {
        "start": "gulp watch",
        "test": "gulp test"
    },
    "version": "0.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
