# npmtest-sift

#### basic test coverage for  sift (v3.3.2)  [![npm package](https://img.shields.io/npm/v/npmtest-sift.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sift) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sift.svg)](https://travis-ci.org/npmtest/node-npmtest-sift)

#### mongodb query style array filtering

[![NPM](https://nodei.co/npm/sift.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sift)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sift/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sift/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sift/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sift/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sift/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sift/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sift/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sift/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sift/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sift/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sift/build/test-report.html](https://npmtest.github.io/node-npmtest-sift/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sift/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sift/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sift/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sift/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sift/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sift/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sift",
    "description": "mongodb query style array filtering",
    "version": "3.3.2",
    "repository": "crcn/sift.js",
    "author": {
        "name": "Craig Condon",
        "url": "http://crcn.io"
    },
    "license": "MIT",
    "engines": {},
    "dependencies": {},
    "typings": "./index.d.ts",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "bson": "^0.2.18",
        "gulp": "^3.9.0",
        "gulp-coveralls": "^0.1.4",
        "gulp-istanbul": "^0.10.0",
        "gulp-jscs": "^1.6.0",
        "gulp-jshint": "^1.11.2",
        "gulp-mocha": "^2.1.2",
        "gulp-plumber": "^1.0.1",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^1.2.0",
        "immutable": "^3.7.6",
        "nodangel": "^1.3.8",
        "yargs": "^3.15.0"
    },
    "main": "./sift.js",
    "scripts": {
        "test": "gulp test-coverage",
        "test-coveralls": "gulp test-coveralls",
        "tdd": "nodangel --ignore node_modules --watch test --watch sift.js --exec 'npm run test'"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
