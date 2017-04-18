# npmdoc-webpack-strip

#### api documentation for  [webpack-strip (v0.1.0)](https://github.com/yahoo/webpack-strip)  [![npm package](https://img.shields.io/npm/v/npmdoc-webpack-strip.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-webpack-strip) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-webpack-strip.svg)](https://travis-ci.org/npmdoc/node-npmdoc-webpack-strip)

#### Webpack loader to strip arbitrary functions out of your production code.

[![NPM](https://nodei.co/npm/webpack-strip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-strip)

- [https://npmdoc.github.io/node-npmdoc-webpack-strip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-strip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-strip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-strip/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-webpack-strip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-webpack-strip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rajiv Tirumalareddy"
    },
    "bugs": {
        "url": "https://github.com/yahoo/webpack-strip/issues"
    },
    "dependencies": {
        "loader-utils": "^0.2.6"
    },
    "description": "Webpack loader to strip arbitrary functions out of your production code.",
    "devDependencies": {
        "chai": "^1.10.0",
        "istanbul": "^0.3.5",
        "jshint": "^2.5.11",
        "mocha": "^2.1.0",
        "webpack": "^1.4.15"
    },
    "directories": {},
    "dist": {
        "shasum": "2737acdd5049502299156a2d6a3ab697239a3359",
        "tarball": "https://registry.npmjs.org/webpack-strip/-/webpack-strip-0.1.0.tgz"
    },
    "gitHead": "21a9124166725da84226550eec37fcf3fef6a9d4",
    "homepage": "https://github.com/yahoo/webpack-strip",
    "jshintConfig": {
        "node": true
    },
    "keywords": [
        "webpack",
        "strip"
    ],
    "licenses": [
        {
            "type": "BSD",
            "url": "https://github.com/yahoo/webpack-strip/blob/master/LICENSE.md"
        }
    ],
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vijar"
        }
    ],
    "name": "webpack-strip",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yahoo/webpack-strip.git"
    },
    "scripts": {
        "cover": "node node_modules/istanbul/lib/cli.js cover --dir artifacts -- ./node_modules/mocha/bin/_mocha tests/unit/ --recursive --reporter spec",
        "lint": "jshint lib tests",
        "test": "mocha tests/unit --recursive --reporter spec"
    },
    "version": "0.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
