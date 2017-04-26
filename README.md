# npmtest-sanitize-html

#### basic test coverage for  [sanitize-html (v1.14.1)](https://github.com/punkave/sanitize-html#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sanitize-html.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sanitize-html) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sanitize-html.svg)](https://travis-ci.org/npmtest/node-npmtest-sanitize-html)

#### Clean up user-submitted HTML, preserving whitelisted elements and whitelisted attributes on a per-element basis

[![NPM](https://nodei.co/npm/sanitize-html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sanitize-html)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sanitize-html/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sanitize-html/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sanitize-html/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sanitize-html/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sanitize-html/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sanitize-html/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sanitize-html/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sanitize-html/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sanitize-html/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sanitize-html/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sanitize-html/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sanitize-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sanitize-html/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sanitize-html/build/test-report.html](https://npmtest.github.io/node-npmtest-sanitize-html/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sanitize-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sanitize-html/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sanitize-html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sanitize-html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sanitize-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sanitize-html/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sanitize-html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sanitize-html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "P'unk Avenue LLC"
    },
    "bugs": {
        "url": "https://github.com/punkave/sanitize-html/issues"
    },
    "dependencies": {
        "htmlparser2": "^3.9.0",
        "regexp-quote": "0.0.0",
        "xtend": "^4.0.0"
    },
    "description": "Clean up user-submitted HTML, preserving whitelisted elements and whitelisted attributes on a per-element basis",
    "devDependencies": {
        "browserify": "^13.0.1",
        "mocha": "^2.5.3",
        "uglify-js": "^2.6.2"
    },
    "directories": {},
    "dist": {
        "shasum": "730ffa2249bdf18333effe45b286173c9c5ad0b8",
        "tarball": "https://registry.npmjs.org/sanitize-html/-/sanitize-html-1.14.1.tgz"
    },
    "gitHead": "fb89a712ba29bed52d5b2a0931b99ed7edf0f00c",
    "homepage": "https://github.com/punkave/sanitize-html#readme",
    "keywords": [
        "html",
        "parser",
        "sanitizer",
        "html",
        "sanitizer",
        "apostrophe"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "alexgilbert"
        },
        {
            "name": "austinstarin"
        },
        {
            "name": "boutell"
        },
        {
            "name": "colpanik"
        },
        {
            "name": "grdunn"
        },
        {
            "name": "jimmyh"
        },
        {
            "name": "kyjoya"
        },
        {
            "name": "mcoppola"
        },
        {
            "name": "stuartromanek"
        }
    ],
    "name": "sanitize-html",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/punkave/sanitize-html.git"
    },
    "scripts": {
        "build": "browserify index.js > dist/sanitize-html.js --standalone 'sanitizeHtml'",
        "minify": "npm run build && uglifyjs dist/sanitize-html.js > dist/sanitize-html.min.js",
        "prebuild": "npm run test && rm -rf dist && mkdir dist",
        "test": "mocha test/test.js"
    },
    "version": "1.14.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
