# npmtest-image-min

#### basic test coverage for  image-min (v0.3.2)  [![npm package](https://img.shields.io/npm/v/npmtest-image-min.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-image-min) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-image-min.svg)](https://travis-ci.org/npmtest/node-npmtest-image-min)

#### Minify GIF, JPEG and PNG images

[![NPM](https://nodei.co/npm/image-min.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/image-min)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-image-min/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-image-min/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-image-min/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-image-min/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-image-min/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-image-min/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-image-min/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-image-min/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-image-min/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-image-min/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-image-min/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-image-min/build/test-report.html](https://npmtest.github.io/node-npmtest-image-min/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-image-min/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-image-min/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-image-min/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-image-min/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-image-min/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-image-min/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-image-min/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-image-min/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "image-min",
    "version": "0.3.2",
    "description": "Minify GIF, JPEG and PNG images",
    "license": "MIT",
    "repository": "kevva/image-min",
    "author": {
        "name": "Kevin Mårtensson",
        "url": "https://github.com/kevva"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "mocha --reporter list --timeout 50000"
    },
    "files": [
        "index.js"
    ],
    "keywords": [
        "extract",
        "tar",
        "tar.gz",
        "zip"
    ],
    "dependencies": {
        "multipipe": "0.0.2",
        "through2": "^0.4.0",
        "win-spawn": "^2.0.0"
    },
    "devDependencies": {
        "mocha": "^1.17.1",
        "rimraf": "^2.2.6"
    },
    "optionalDependencies": {
        "gifsicle": "^0.1.0",
        "jpegtran-bin": "^0.2.0",
        "optipng-bin": "^0.3.2",
        "pngquant-bin": "^0.1.6"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
