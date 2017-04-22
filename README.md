# npmdoc-snappy

#### api documentation for  [snappy (v6.0.0)](https://github.com/kesla/node-snappy)  [![npm package](https://img.shields.io/npm/v/npmdoc-snappy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-snappy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-snappy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-snappy)

#### Nodejs bindings to Google's Snappy compression library

[![NPM](https://nodei.co/npm/snappy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/snappy)

- [https://npmdoc.github.io/node-npmdoc-snappy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-snappy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-snappy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-snappy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-snappy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-snappy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Björklund"
    },
    "bugs": {
        "url": "https://github.com/kesla/node-snappy/issues"
    },
    "dependencies": {
        "bindings": "1.2.1",
        "nan": "2.4.0",
        "node-gyp": "3.4.0"
    },
    "description": "Nodejs bindings to Google's Snappy compression library",
    "devDependencies": {
        "ava": "^0.16.0",
        "bluebird": "^3.3.4",
        "nyc": "^8.3.0",
        "semistandard": "^9.0.0",
        "snazzy": "^5.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "43f6d17ae78f3e261c8e817dca183844ac5b4649",
        "tarball": "https://registry.npmjs.org/snappy/-/snappy-6.0.0.tgz"
    },
    "gitHead": "75f582408acb4d519237b93a9b03f6ef12617f33",
    "gypfile": true,
    "homepage": "https://github.com/kesla/node-snappy",
    "license": "MIT",
    "main": "snappy.js",
    "maintainers": [
        {
            "name": "kesla"
        }
    ],
    "name": "snappy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/kesla/node-snappy.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "nyc ava test.js && semistandard | snazzy"
    },
    "version": "6.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
