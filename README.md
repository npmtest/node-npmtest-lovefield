# npmtest-lovefield

#### basic test coverage for  [lovefield (v2.1.12)](https://github.com/google/lovefield)  [![npm package](https://img.shields.io/npm/v/npmtest-lovefield.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lovefield) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lovefield.svg)](https://travis-ci.org/npmtest/node-npmtest-lovefield)

#### Lovefield - A relational database for web apps

[![NPM](https://nodei.co/npm/lovefield.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lovefield)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lovefield/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lovefield/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lovefield/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lovefield/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lovefield/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lovefield/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lovefield/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lovefield/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lovefield/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lovefield/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lovefield/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lovefield/build/test-report.html](https://npmtest.github.io/node-npmtest-lovefield/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lovefield/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lovefield/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lovefield/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lovefield/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lovefield/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lovefield/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lovefield/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lovefield/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "lovefield",
    "version": "2.1.12",
    "main": "dist/lovefield.min.js",
    "description": "Lovefield - A relational database for web apps",
    "keywords": [
        "lovefield"
    ],
    "homepage": "https://github.com/google/lovefield",
    "bugs": {
        "url": "https://github.com/google/lovefield/issues"
    },
    "license": "Apache-2.0",
    "repository": {
        "type": "git",
        "url": "https://github.com/google/lovefield.git"
    },
    "files": [
        "dist",
        "spac/codegen.js",
        "spac/lovefield-spac",
        "spac/parser.js",
        "spac/spac.js",
        "spac/template"
    ],
    "bin": {
        "lovefield-spac": "spac/lovefield-spac"
    },
    "dependencies": {
        "js-yaml": "~3.1.0",
        "nopt": "~2.2.1"
    },
    "devDependencies": {
        "chalk": "^0.5.1",
        "firebase-token-generator": "*",
        "fs-extra": "^0.18.2",
        "glob": "~3.2.6",
        "google-closure-compiler": "latest",
        "google-closure-library": "latest",
        "gulp": "^3.9.0",
        "gulp-closure-compiler": "0.3.1",
        "gulp-connect": "^2.2.0",
        "gulp-gjslint": "^0.1.4",
        "jasmine": "^2.3.2",
        "mkdirp": "^0.5.0",
        "request": "^2.55.0",
        "selenium-webdriver": "2.47.0",
        "temporary": "^0.0.8",
        "toposort-class": "^0.3.1"
    },
    "engines": {
        "node": ">=4.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
