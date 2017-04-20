# npmtest-nan

#### basic test coverage for  [nan (v2.6.2)](https://github.com/nodejs/nan#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nan.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nan) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nan.svg)](https://travis-ci.org/npmtest/node-npmtest-nan)

#### Native Abstractions for Node.js: C++ header for Node 0.8 -> 7 compatibility

[![NPM](https://nodei.co/npm/nan.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nan)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nan/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nan/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nan/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nan/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nan/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nan/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nan/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nan/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nan/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nan/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nan/build/test-report.html](https://npmtest.github.io/node-npmtest-nan/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nan/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nan/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nan/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nan/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nan/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nan/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nan/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/nodejs/nan/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "Benjamin Byholm",
            "url": "https://github.com/kkoopa/"
        },
        {
            "name": "Trevor Norris",
            "url": "https://github.com/trevnorris"
        },
        {
            "name": "Nathan Rajlich",
            "url": "https://github.com/TooTallNate"
        },
        {
            "name": "Brett Lawson",
            "url": "https://github.com/brett19"
        },
        {
            "name": "Ben Noordhuis",
            "url": "https://github.com/bnoordhuis"
        },
        {
            "name": "David Siegel",
            "url": "https://github.com/agnat"
        },
        {
            "name": "Michael Ira Krufky",
            "url": "https://github.com/mkrufky"
        }
    ],
    "dependencies": {},
    "description": "Native Abstractions for Node.js: C++ header for Node 0.8 -> 7 compatibility",
    "devDependencies": {
        "bindings": "~1.2.1",
        "commander": "^2.8.1",
        "glob": "^5.0.14",
        "node-gyp": "~3.0.1",
        "readable-stream": "^2.1.4",
        "tap": "~0.7.1",
        "xtend": "~4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e4ff34e6c95fdfb5aecc08de6596f43605a7db45",
        "tarball": "https://registry.npmjs.org/nan/-/nan-2.6.2.tgz"
    },
    "gitHead": "f0b2f64c1e5317888f2e12fdefb2f105e7018552",
    "homepage": "https://github.com/nodejs/nan#readme",
    "license": "MIT",
    "main": "include_dirs.js",
    "maintainers": [
        {
            "name": "rvagg"
        },
        {
            "name": "kkoopa"
        }
    ],
    "name": "nan",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/nodejs/nan.git"
    },
    "scripts": {
        "docs": "doc/.build.sh",
        "rebuild-tests": "node-gyp rebuild --msvs_version=2013 --directory test",
        "test": "tap --gc --stderr test/js/*-test.js"
    },
    "version": "2.6.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
