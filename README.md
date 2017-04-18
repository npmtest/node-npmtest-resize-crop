# npmtest-resize-crop

#### test coverage for  [resize-crop (v0.0.3)](https://github.com/traviswimer/resize-crop.js)  [![npm package](https://img.shields.io/npm/v/npmtest-resize-crop.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-resize-crop) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-resize-crop.svg)](https://travis-ci.org/npmtest/node-npmtest-resize-crop)

#### Make images a specific size without distorting the aspect ratio. Resizes as close as possible and crops the rest.

[![NPM](https://nodei.co/npm/resize-crop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/resize-crop)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-resize-crop/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-resize-crop/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-resize-crop/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-resize-crop/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-resize-crop/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-resize-crop/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-resize-crop/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-resize-crop/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-resize-crop/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-resize-crop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-resize-crop/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-resize-crop/build/test-report.html](https://npmtest.github.io/node-npmtest-resize-crop/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-resize-crop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-resize-crop/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-resize-crop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-resize-crop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-resize-crop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-resize-crop/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-resize-crop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-resize-crop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Travis Wimer",
        "url": "http://traviswimer.com"
    },
    "bugs": {
        "url": "https://github.com/traviswimer/resize-crop.js/issues"
    },
    "dependencies": {
        "deep-extend": "~0.2.8",
        "image-size": "~0.2.1",
        "imagemagick": "~0.1.3"
    },
    "description": "Make images a specific size without distorting the aspect ratio. Resizes as close as possible and crops the rest.",
    "devDependencies": {
        "chai": "~1.9.0",
        "grunt": "~0.4.4",
        "grunt-cli": "~0.1.13",
        "grunt-contrib-clean": "~0.4.0",
        "grunt-contrib-jshint": "~0.6.0",
        "grunt-contrib-watch": "~0.6.0",
        "grunt-coveralls": "~0.3.0",
        "grunt-env": "~0.4.1",
        "grunt-mocha-test": "~0.10.0",
        "grunt-not-constantinople": "0.0.2",
        "image-size": "~0.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b230becca1b9f9246f6d14e8ce99d9930230636a",
        "tarball": "https://registry.npmjs.org/resize-crop/-/resize-crop-0.0.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "homepage": "https://github.com/traviswimer/resize-crop.js",
    "keywords": [
        "images",
        "resize",
        "crop"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/traviswimer/resize-crop.js/blob/master/LICENSE-MIT"
        }
    ],
    "main": "src/resize-crop",
    "maintainers": [
        {
            "name": "traviswimer"
        }
    ],
    "name": "resize-crop",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/traviswimer/resize-crop.js.git"
    },
    "scripts": {
        "ci": "grunt test --stack",
        "test": "grunt test"
    },
    "version": "0.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
