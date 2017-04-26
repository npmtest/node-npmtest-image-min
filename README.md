# npmtest-image-min

#### basic test coverage for  [image-min (v0.3.2)](https://github.com/kevva/image-min)  [![npm package](https://img.shields.io/npm/v/npmtest-image-min.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-image-min) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-image-min.svg)](https://travis-ci.org/npmtest/node-npmtest-image-min)

#### Minify GIF, JPEG and PNG images

[![NPM](https://nodei.co/npm/image-min.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/image-min)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-image-min/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-image-min/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-image-min/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-image-min/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-image-min/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-image-min/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-image-min/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-image-min/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-image-min/tree/gh-pages/build)|

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
    "author": {
        "name": "Kevin Mårtensson",
        "url": "https://github.com/kevva"
    },
    "bugs": {
        "url": "https://github.com/kevva/image-min/issues"
    },
    "dependencies": {
        "gifsicle": "^0.1.0",
        "jpegtran-bin": "^0.2.0",
        "multipipe": "0.0.2",
        "optipng-bin": "^0.3.2",
        "pngquant-bin": "^0.1.6",
        "through2": "^0.4.0",
        "win-spawn": "^2.0.0"
    },
    "description": "Minify GIF, JPEG and PNG images",
    "devDependencies": {
        "mocha": "^1.17.1",
        "rimraf": "^2.2.6"
    },
    "directories": {},
    "dist": {
        "shasum": "b669a4d31f29d06f84537df062b7edc25b73fa16",
        "tarball": "https://registry.npmjs.org/image-min/-/image-min-0.3.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "c0ea01372441fb8924e9f5fd71238595a55de2d9",
    "homepage": "https://github.com/kevva/image-min",
    "keywords": [
        "extract",
        "tar",
        "tar.gz",
        "zip"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kevva"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "image-min",
    "optionalDependencies": {
        "gifsicle": "^0.1.0",
        "jpegtran-bin": "^0.2.0",
        "optipng-bin": "^0.3.2",
        "pngquant-bin": "^0.1.6"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kevva/image-min.git"
    },
    "scripts": {
        "test": "mocha --reporter list --timeout 50000"
    },
    "version": "0.3.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
