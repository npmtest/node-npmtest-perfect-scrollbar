# npmtest-perfect-scrollbar

#### basic test coverage for  [perfect-scrollbar (v0.6.16)](https://github.com/noraesae/perfect-scrollbar#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-perfect-scrollbar.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-perfect-scrollbar) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-perfect-scrollbar.svg)](https://travis-ci.org/npmtest/node-npmtest-perfect-scrollbar)

#### Minimalistic but perfect custom scrollbar plugin

[![NPM](https://nodei.co/npm/perfect-scrollbar.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/perfect-scrollbar)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-perfect-scrollbar/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-perfect-scrollbar/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-perfect-scrollbar/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/test-report.html](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-perfect-scrollbar/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-perfect-scrollbar/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-perfect-scrollbar/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-perfect-scrollbar/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-perfect-scrollbar/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hyunje Jun"
    },
    "bugs": {
        "url": "https://github.com/noraesae/perfect-scrollbar/issues"
    },
    "contributors": [
        {
            "name": "Hyunje Jun"
        }
    ],
    "dependencies": {},
    "description": "Minimalistic but perfect custom scrollbar plugin",
    "devDependencies": {
        "browserify": "^11.2.0",
        "del": "^2.0.2",
        "event-stream": "^3.3.1",
        "gulp": "^3.9.0",
        "gulp-autoprefixer": "^3.1.0",
        "gulp-connect": "^2.2.0",
        "gulp-eslint": "^1.0.0",
        "gulp-insert": "^0.5.0",
        "gulp-rename": "^1.2.2",
        "gulp-sass": "^2.0.4",
        "gulp-uglify": "^1.4.1",
        "gulp-zip": "^3.0.2",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b1d61a5245cf3962bb9a8407a3fc669d923212fc",
        "tarball": "https://registry.npmjs.org/perfect-scrollbar/-/perfect-scrollbar-0.6.16.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "files": [
        "dist",
        "src",
        "index.js",
        "jquery.js",
        "perfect-scrollbar.d.ts"
    ],
    "gitHead": "ce3a199cb3b4d999cb114e433d5966a7a0ca989e",
    "homepage": "https://github.com/noraesae/perfect-scrollbar#readme",
    "jspm": {
        "main": "./index.js",
        "registry": "jspm"
    },
    "keywords": [
        "jquery-plugin",
        "frontend",
        "scroll",
        "scrollbar"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "noraesae"
        }
    ],
    "name": "perfect-scrollbar",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/noraesae/perfect-scrollbar.git"
    },
    "scripts": {
        "before-deploy": "gulp && gulp compress",
        "release": "rm -rf dist && gulp && npm publish",
        "test": "gulp"
    },
    "typings": "perfect-scrollbar.d.ts",
    "version": "0.6.16"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
