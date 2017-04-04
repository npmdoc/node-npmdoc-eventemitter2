# api documentation for  [eventemitter2 (v4.1.0)](https://github.com/hij1nx/EventEmitter2#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-eventemitter2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eventemitter2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eventemitter2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eventemitter2)
#### A Node.js event emitter implementation with namespaces, wildcards, TTL and browser support.

[![NPM](https://nodei.co/npm/eventemitter2.png?downloads=true)](https://www.npmjs.com/package/eventemitter2)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eventemitter2_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eventemitter2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hij1nx",
        "email": "paolo@async.ly"
    },
    "bugs": {
        "url": "https://github.com/hij1nx/EventEmitter2/issues"
    },
    "contributors": [
        {
            "name": "Eric Elliott"
        },
        {
            "name": "Charlie Robbins",
            "email": "charlie@nodejitsu.com"
        },
        {
            "name": "Jameson Lee",
            "email": "jameson@nodejitsu.com"
        },
        {
            "name": "Jeroen van Duffelen",
            "email": "jvduf@nodejitsu.com"
        },
        {
            "name": "Fedor Indutny",
            "email": "fedor.indutny@gmail.com"
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
            "name": "hij1nx",
            "email": "paolo@async.ly"
        },
        {
            "name": "rangermauve",
            "email": "rangermauve@hotmail.com"
        }
    ],
    "name": "eventemitter2",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eventemitter2](#apidoc.module.eventemitter2)
1.  [function <span class="apidocSignatureSpan">eventemitter2.</span>EventEmitter2 (conf)](#apidoc.element.eventemitter2.EventEmitter2)



# <a name="apidoc.module.eventemitter2"></a>[module eventemitter2](#apidoc.module.eventemitter2)

#### <a name="apidoc.element.eventemitter2.EventEmitter2"></a>[function <span class="apidocSignatureSpan">eventemitter2.</span>EventEmitter2 (conf)](#apidoc.element.eventemitter2.EventEmitter2)
- description and source-code
```javascript
function EventEmitter(conf) {
  this._events = {};
  this.newListener = false;
  this.verboseMemoryLeak = false;
  configure.call(this, conf);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
