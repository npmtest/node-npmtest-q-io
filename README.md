# npmtest-q-io

#### basic test coverage for  [q-io (v1.13.2)](http://github.com/kriskowal/q-io/)  [![npm package](https://img.shields.io/npm/v/npmtest-q-io.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-q-io) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-q-io.svg)](https://travis-ci.org/npmtest/node-npmtest-q-io)

#### IO using Q promises

[![NPM](https://nodei.co/npm/q-io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/q-io)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-q-io/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-q-io/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-q-io/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-q-io/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-q-io/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-q-io/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-q-io/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-q-io/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-q-io/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-q-io/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-q-io/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-q-io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-q-io/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-q-io/build/test-report.html](https://npmtest.github.io/node-npmtest-q-io/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-q-io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-q-io/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-q-io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-q-io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-q-io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-q-io/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-q-io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-q-io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kris Kowal",
        "url": "http://github.com/kriskowal/"
    },
    "bugs": {
        "url": "http://github.com/kriskowal/q-io/issues"
    },
    "contributors": [
        {
            "name": "Montage Studio"
        },
        {
            "name": "Stuart Knightley"
        },
        {
            "name": "Jean-romain Prevost"
        },
        {
            "name": "Andreas Pizsa",
            "url": "http://github.com/AndreasPizsa/"
        }
    ],
    "dependencies": {
        "collections": "^0.2.0",
        "mime": "^1.2.11",
        "mimeparse": "^0.1.4",
        "q": "^1.0.1",
        "qs": "^1.2.1",
        "url2": "^0.0.0"
    },
    "description": "IO using Q promises",
    "devDependencies": {
        "cover": "^0.2.8",
        "jasmine-node": "^1.7",
        "jshint": "^0.9.1",
        "opener": "^1.3"
    },
    "directories": {},
    "dist": {
        "shasum": "eea130d481ddb5e1aa1bc5a66855f7391d06f003",
        "tarball": "https://registry.npmjs.org/q-io/-/q-io-1.13.2.tgz"
    },
    "engines": {
        "node": ">=0.6.0"
    },
    "gitHead": "e282c3b7d0e1c1046265930842c6a16693b928d6",
    "homepage": "http://github.com/kriskowal/q-io/",
    "license": "MIT",
    "maintainers": [
        {
            "name": "arikon"
        },
        {
            "name": "gagern"
        },
        {
            "name": "kriskowal"
        }
    ],
    "name": "q-io",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/kriskowal/q-io.git"
    },
    "scripts": {
        "cover": "cover run jasmine-node spec && cover report html && opener cover_html/index.html",
        "lint": "jshint q.js",
        "test": "jasmine-node spec",
        "test-browser": "opener spec/q-spec.html"
    },
    "version": "1.13.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
