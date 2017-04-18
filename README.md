# test coverage for  [browserify-css (v0.10.0)](http://cheton.github.io/browserify-css/)  [![npm package](https://img.shields.io/npm/v/npmtest-browserify-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-browserify-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-browserify-css.svg)](https://travis-ci.org/npmtest/node-npmtest-browserify-css)
#### A Browserify transform for bundling, rebasing, inlining, and minifying CSS files

[![NPM](https://nodei.co/npm/browserify-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browserify-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-browserify-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-browserify-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-browserify-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-browserify-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-browserify-css/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-browserify-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-browserify-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-browserify-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-browserify-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-browserify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-browserify-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-browserify-css/build/test-report.html](https://npmtest.github.io/node-npmtest-browserify-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-browserify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-browserify-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-browserify-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browserify-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browserify-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browserify-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-browserify-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-browserify-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cheton Wu"
    },
    "browser": "./browser.js",
    "bugs": {
        "url": "https://github.com/cheton/browserify-css/issues"
    },
    "dependencies": {
        "clean-css": "2.2.x",
        "concat-stream": "1.4.x",
        "css": "1.6.x",
        "find-node-modules": "^1.0.1",
        "lodash": "3.6.x",
        "mime": "~1.2.11",
        "through2": "0.6.x"
    },
    "description": "A Browserify transform for bundling, rebasing, inlining, and minifying CSS files",
    "devDependencies": {
        "browserify": "^12.0.1",
        "coveralls": "^2.11.8",
        "del": "^1.1.1",
        "exorcist": "^0.1.6",
        "fs-extra": "^0.18.0",
        "gulp": "^3.9.0",
        "gulp-jshint": "^1.9.2",
        "gulp-util": "^3.0.4",
        "jsdom": "^8.1.0",
        "require-dir": "^0.3.0",
        "run-sequence": "^1.0.2",
        "tap": "^5.7.0",
        "vinyl-source-stream": "^1.1.0",
        "yargs": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f3eb0f35cbe1fee02a03de2b8c83c5d499dd794d",
        "tarball": "https://registry.npmjs.org/browserify-css/-/browserify-css-0.10.0.tgz"
    },
    "gitHead": "32f461bce3461ae05a72f0c056e35035ab8f24f0",
    "homepage": "http://cheton.github.io/browserify-css/",
    "keywords": [
        "browser",
        "browserify",
        "browserify-transform",
        "css",
        "dom",
        "minify",
        "transform"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "cheton"
        }
    ],
    "name": "browserify-css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cheton/browserify-css.git"
    },
    "scripts": {
        "build": "gulp",
        "coveralls": "tap --coverage --coverage-report=text-lcov test/*.js | node_modules/.bin/coveralls",
        "prepublish": "npm run build && npm test",
        "test": "gulp && node_modules/.bin/tap --coverage test/*.js"
    },
    "version": "0.10.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
