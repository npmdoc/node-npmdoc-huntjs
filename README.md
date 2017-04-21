# npmdoc-huntjs

#### api documentation for  [huntjs (v3.0.0)](https://github.com/jeremenichelli/hunt#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-huntjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-huntjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-huntjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-huntjs)

#### Library to detect when DOM elements become visible and disappear on scroll

[![NPM](https://nodei.co/npm/huntjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/huntjs)

- [https://npmdoc.github.io/node-npmdoc-huntjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-huntjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-huntjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-huntjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-huntjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-huntjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "huntjs",
    "title": "Hunt",
    "version": "3.0.0",
    "description": "Library to detect when DOM elements become visible and disappear on scroll",
    "main": "dist/hunt.js",
    "scripts": {
        "lint": "eslint src/**/*.js",
        "prebuild": "npm run lint && mkdir -p dist",
        "build": "ncp src/hunt.js dist/hunt.js & uglifyjs src/hunt.js > dist/hunt.min.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jeremenichelli/hunt.git"
    },
    "keywords": [
        "hunt",
        "scroll",
        "dom",
        "element"
    ],
    "author": "Jeremias Menichelli",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/jeremenichelli/hunt/issues"
    },
    "homepage": "https://github.com/jeremenichelli/hunt#readme",
    "devDependencies": {
        "eslint": "^1.10.3",
        "ncp": "^2.0.0",
        "uglify-js": "^2.6.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
