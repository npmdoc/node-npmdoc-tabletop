# npmdoc-tabletop

#### basic api documentation for  [tabletop (v1.5.2)](https://github.com/jsoma/tabletop#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-tabletop.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-tabletop) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-tabletop.svg)](https://travis-ci.org/npmdoc/node-npmdoc-tabletop)

#### **Tabletop.js** takes a Google Spreadsheet and makes it easily accessible through JavaScript. With zero dependencies!

[![NPM](https://nodei.co/npm/tabletop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tabletop)

- [https://npmdoc.github.io/node-npmdoc-tabletop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tabletop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tabletop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tabletop/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-tabletop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-tabletop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Soma"
    },
    "bugs": {
        "url": "https://github.com/jsoma/tabletop/issues"
    },
    "dependencies": {
        "nsp": "^2.6.2",
        "request": "^2.51.0"
    },
    "description": "**Tabletop.js** takes a Google Spreadsheet and makes it easily accessible through JavaScript. With zero dependencies!",
    "devDependencies": {
        "chai": "^3.5.0",
        "grunt": "*",
        "grunt-contrib-connect": "*",
        "grunt-contrib-jshint": "^1.1.0",
        "grunt-contrib-uglify": "^2.0.0",
        "jshint-stylish": "^2.0.0",
        "mocha": "^3.2.0",
        "uglifyjs": "^2.4.10"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "654d484cae4e0e65a1f2077a7bec60da7b7464f3",
        "tarball": "https://registry.npmjs.org/tabletop/-/tabletop-1.5.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "fdb1c3ee3bc0f7f3be6ab223a56f9f050fe32496",
    "homepage": "https://github.com/jsoma/tabletop#readme",
    "license": "MIT",
    "main": "src/tabletop.js",
    "maintainers": [
        {
            "name": "jsoma"
        }
    ],
    "name": "tabletop",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jsoma/tabletop.git"
    },
    "scripts": {
        "test": "node node_modules/mocha/bin/mocha --timeout 5000 && node node_modules/nsp/bin/nsp check",
        "uglify": "node node_modules/uglifyjs/bin/uglifyjs src/tabletop.js > src/tabletop.min.js "
    },
    "version": "1.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
