# test coverage for  [jslint (v0.10.3)](https://github.com/reid/node-jslint)  [![npm package](https://img.shields.io/npm/v/npmtest-jslint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jslint.svg)](https://travis-ci.org/npmtest/node-npmtest-jslint)
#### The JavaScript Code Quality Tool

[![NPM](https://nodei.co/npm/jslint.png?downloads=true)](https://www.npmjs.com/package/jslint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jslint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jslint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jslint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jslint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jslint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jslint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jslint/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jslint/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-jslint/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-jslint/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-jslint%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jslint/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jslint/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-jslint%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jslint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Reid Burke",
        "email": "me@reidburke.com"
    },
    "bin": {
        "jslint": "./bin/jslint.js"
    },
    "bugs": {
        "url": "https://github.com/reid/node-jslint/issues"
    },
    "contributors": [
        {
            "name": "Douglas Crockford",
            "email": "douglas@crockford.com"
        },
        {
            "name": "Mikeal Rogers",
            "email": "mikeal.rogers@gmail.com"
        },
        {
            "name": "Adam Moore"
        },
        {
            "name": "Luke Smith",
            "email": "lsmith@yahoo-inc.com"
        },
        {
            "name": "Anders Conbere",
            "email": "aconbere@gmail.com"
        },
        {
            "name": "Ryuichi OKUMURA",
            "email": "okuryu@okuryu.com"
        },
        {
            "name": "Sam Mikes",
            "email": "smikes@cubane.com"
        },
        {
            "name": "Dylan Lloyd"
        },
        {
            "name": "Andreas Hindborg"
        },
        {
            "name": "Andrew Pennebaker"
        },
        {
            "name": "Bnaya"
        },
        {
            "name": "Maximilian Antoni",
            "email": "mail@maxantoni.de"
        },
        {
            "name": "Vasil Velichkov"
        },
        {
            "name": "Rasmus Paetau"
        },
        {
            "name": "Bryan Horna"
        }
    ],
    "dependencies": {
        "exit": "~0.1.2",
        "glob": "^7.0.3",
        "nopt": "~3.0.1",
        "readable-stream": "~2.1.2"
    },
    "description": "The JavaScript Code Quality Tool",
    "devDependencies": {
        "fs.extra": "^1.3.2",
        "istanbul": "^0.4.3",
        "marked-man": "~0.1.5",
        "mocha": "^3.0.0"
    },
    "directories": {
        "lib": "./lib",
        "man": "./man",
        "doc": "./doc"
    },
    "dist": {
        "shasum": "890da3e79932edf06c5f4b52a7b5ba6436867436",
        "tarball": "https://registry.npmjs.org/jslint/-/jslint-0.10.3.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "files": [
        "man/jslint.1",
        "doc/jslint.md",
        "doc/jslint.html",
        "lib",
        "bin",
        "jslint.conf.example",
        "Makefile"
    ],
    "gitHead": "c2cdb60176983c5e4e93aebbcba1d8c2c93ac416",
    "homepage": "https://github.com/reid/node-jslint",
    "keywords": [
        "lint",
        "jslint",
        "code-quality",
        "static-analysis",
        "jshint",
        "eslint"
    ],
    "license": "BSD-3-Clause",
    "licenses": [
        {
            "type": "Modified MIT / BSD",
            "url": "https://github.com/reid/node-jslint/blob/master/LICENSE"
        }
    ],
    "main": "./lib/nodelint.js",
    "maintainers": [
        {
            "name": "reid",
            "email": "me@reidburke.com"
        },
        {
            "name": "okuryu",
            "email": "okuryu@okuryu.com"
        },
        {
            "name": "smikes",
            "email": "smikes@cubane.com"
        }
    ],
    "man": [
        "man/jslint.1"
    ],
    "name": "jslint",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/reid/node-jslint.git"
    },
    "scripts": {
        "mypublish": "make prepublish; npm publish",
        "test": "make test"
    },
    "version": "0.10.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
