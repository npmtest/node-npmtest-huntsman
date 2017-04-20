# npmtest-huntsman

#### basic test coverage for  [huntsman (v0.3.0)](https://github.com/missinglink/huntsman#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-huntsman.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-huntsman) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-huntsman.svg)](https://travis-ci.org/npmtest/node-npmtest-huntsman)

#### Super configurable async web spider

[![NPM](https://nodei.co/npm/huntsman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/huntsman)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-huntsman/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-huntsman/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-huntsman/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-huntsman/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-huntsman/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-huntsman/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-huntsman/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-huntsman/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-huntsman/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-huntsman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-huntsman/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-huntsman/build/test-report.html](https://npmtest.github.io/node-npmtest-huntsman/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-huntsman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-huntsman/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-huntsman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-huntsman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-huntsman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-huntsman/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-huntsman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-huntsman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Peter Johnson",
        "url": "https://github.com/missinglink/"
    },
    "bugs": {
        "url": "http://github.com/missinglink/huntsman/issues"
    },
    "dependencies": {
        "async": "0.7.0",
        "cheerio": "^0.19.0",
        "regexemitter": "0.2.3",
        "semver": "3.0.1",
        "superagent": "0.18.0"
    },
    "description": "Super configurable async web spider",
    "devDependencies": {
        "breakdown": "*",
        "coffee-script": "*",
        "mocha": "*",
        "should": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "f11858152c6e5f3b5c6bee51da2c901e3968681c",
        "tarball": "https://registry.npmjs.org/huntsman/-/huntsman-0.3.0.tgz"
    },
    "engines": {
        "node": ">0.10.0",
        "npm": ">1.1.x"
    },
    "gitHead": "38ef6b92a1f14bd761a5de5b2612283d7b3f6ded",
    "homepage": "https://github.com/missinglink/huntsman#readme",
    "keywords": [
        "spider",
        "crawler",
        "crawl",
        "huntsman",
        "robot",
        "aync"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "maintainers": [
        {
            "name": "missinglink"
        }
    ],
    "name": "huntsman",
    "optionalDependencies": {},
    "preferGlobal": false,
    "private": false,
    "repository": {
        "type": "git",
        "url": "git://github.com/missinglink/huntsman.git"
    },
    "scripts": {
        "test": "node node_modules/mocha/bin/mocha --recursive --reporter spec --compilers coffee:coffee-script/register test"
    },
    "version": "0.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
