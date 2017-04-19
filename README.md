# npmtest-express-winston

#### test coverage for  [express-winston (v2.3.0)](https://github.com/bithavoc/express-winston#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-winston.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-winston) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-winston.svg)](https://travis-ci.org/npmtest/node-npmtest-express-winston)

#### express.js middleware for flatiron/winston

[![NPM](https://nodei.co/npm/express-winston.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-winston)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-winston/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-winston/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-winston/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-winston/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-winston/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-winston/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-winston/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-winston/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-winston/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-winston/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-winston/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-winston/build/test-report.html](https://npmtest.github.io/node-npmtest-express-winston/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-winston/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-winston/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-winston/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-winston/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-winston/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-winston/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-winston/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-winston/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "bithavoc",
        "url": "http://bithavoc.io"
    },
    "bugs": {
        "url": "http://github.com/bithavoc/express-winston/issues"
    },
    "config": {
        "travis-cov": {
            "threshold": 100
        },
        "blanket": {
            "pattern": [
                "index.js"
            ],
            "data-cover-never": [
                "node_modules",
                "test"
            ]
        }
    },
    "contributors": [
        {
            "name": "Lars Jacob",
            "url": "http://jaclar.net"
        },
        {
            "name": "Jonathan Lomas",
            "url": "http://floatinglomas.ca"
        },
        {
            "name": "Xavier Damman",
            "url": "http://xdamman.com"
        },
        {
            "name": "Quentin Rossetti"
        },
        {
            "name": "Robbie Trencheny",
            "url": "http://robbie.io"
        }
    ],
    "dependencies": {
        "chalk": "~0.4.0",
        "lodash": "~4.11.1"
    },
    "description": "express.js middleware for flatiron/winston",
    "devDependencies": {
        "blanket": "^1.2.2",
        "mocha": "^2.4.5",
        "node-mocks-http": "^1.5.1",
        "promise": "^7.1.1",
        "should": "^8.2.2",
        "travis-cov": "^0.2.5",
        "winston": ">=1.x"
    },
    "directories": {},
    "dist": {
        "shasum": "8dea98617f96a53cc9c073159d08b0dc38c5f231",
        "tarball": "https://registry.npmjs.org/express-winston/-/express-winston-2.3.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "69456f1112db2a2c73621679ef684ffd690704f2",
    "homepage": "https://github.com/bithavoc/express-winston#readme",
    "keywords": [
        "winston",
        "flatiron",
        "logging",
        "express",
        "log",
        "error",
        "handler",
        "middleware",
        "colors"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bithavoc"
        },
        {
            "name": "floatinglomas"
        },
        {
            "name": "rosston"
        }
    ],
    "name": "express-winston",
    "optionalDependencies": {},
    "peerDependencies": {
        "winston": ">=1.x"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bithavoc/express-winston.git"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "test-coverage": "mocha --require blanket --reporter html-cov > coverage.html || true",
        "test-travis": "mocha --require blanket --reporter travis-cov"
    },
    "version": "2.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
