# npmtest-dom4

#### basic test coverage for  [dom4 (v1.8.3)](https://github.com/WebReflection/dom4)  [![npm package](https://img.shields.io/npm/v/npmtest-dom4.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dom4) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dom4.svg)](https://travis-ci.org/npmtest/node-npmtest-dom4)

#### a fully tested and covered polyfill for new DOM Level 4 entries

[![NPM](https://nodei.co/npm/dom4.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dom4)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dom4/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dom4/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dom4/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dom4/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dom4/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dom4/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dom4/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dom4/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dom4/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dom4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dom4/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dom4/build/test-report.html](https://npmtest.github.io/node-npmtest-dom4/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dom4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dom4/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dom4/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dom4/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dom4/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dom4/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dom4/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dom4/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "dom4",
    "title": "DOM4",
    "description": "a fully tested and covered polyfill for new DOM Level 4 entries",
    "version": "1.8.3",
    "main": "build/dom4.max.js",
    "homepage": "https://github.com/WebReflection/dom4",
    "author": {
        "name": "Andrea Giammarchi",
        "url": "http://webreflection.blogspot.com"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/WebReflection/dom4.git"
    },
    "keywords": [
        "DOM",
        "Level 4",
        "classList",
        "CustomEvent",
        "DOM4"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/jquery/jquery/blob/master/MIT-LICENSE.txt"
        }
    ],
    "scripts": {
        "test": "phantomjs testrunner.js",
        "web": "node node_modules/tiny-cdn/tiny-cdn run -p=1337"
    },
    "dependencies": {},
    "devDependencies": {
        "wru": "~0.2.x",
        "uglify-js": "1.x",
        "jshint": "~2.x",
        "tiny-cdn": "*",
        "phantomjs": "~1.x"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
