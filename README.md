# npmdoc-eventemitter2

#### api documentation for  [eventemitter2 (v4.1.0)](https://github.com/hij1nx/EventEmitter2#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-eventemitter2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eventemitter2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eventemitter2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eventemitter2)

#### A Node.js event emitter implementation with namespaces, wildcards, TTL and browser support.

[![NPM](https://nodei.co/npm/eventemitter2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eventemitter2)

- [https://npmdoc.github.io/node-npmdoc-eventemitter2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hij1nx"
    },
    "bugs": {
        "url": "https://github.com/hij1nx/EventEmitter2/issues"
    },
    "contributors": [
        {
            "name": "Eric Elliott"
        },
        {
            "name": "Charlie Robbins"
        },
        {
            "name": "Jameson Lee"
        },
        {
            "name": "Jeroen van Duffelen"
        },
        {
            "name": "Fedor Indutny"
        }
    ],
    "dependencies": {},
    "description": "A Node.js event emitter implementation with namespaces, wildcards, TTL and browser support.",
    "devDependencies": {
        "benchmark": ">= 0.2.2",
        "nodeunit": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "b1fb8a1144e7dfcf80cecce9877ff6d68e7d8506",
        "tarball": "https://registry.npmjs.org/eventemitter2/-/eventemitter2-4.1.0.tgz"
    },
    "files": [
        "lib/eventemitter2.js",
        "index.js",
        "eventemitter2.d.ts"
    ],
    "gitHead": "c5da5e3fae76cdc0596e651a72d313728302f95a",
    "homepage": "https://github.com/hij1nx/EventEmitter2#readme",
    "keywords": [
        "event",
        "events",
        "emitter",
        "eventemitter"
    ],
    "license": "MIT",
    "main": "./lib/eventemitter2.js",
    "maintainers": [
        {
            "name": "hij1nx"
        },
        {
            "name": "rangermauve"
        }
    ],
    "name": "eventemitter2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hij1nx/EventEmitter2.git"
    },
    "scripts": {
        "benchmark": "node test/perf/benchmark.js",
        "test": "nodeunit test/simple/ && nodeunit test/wildcardEvents/"
    },
    "typescript": {
        "definition": "./eventemitter2.d.ts"
    },
    "typings": "./eventemitter2.d.ts",
    "version": "4.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
