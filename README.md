# npmtest-oracledb

#### basic test coverage for  [oracledb (v1.13.1)](http://www.oracle.com/technetwork/database/database-technologies/scripting-languages/node_js/)  [![npm package](https://img.shields.io/npm/v/npmtest-oracledb.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-oracledb) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-oracledb.svg)](https://travis-ci.org/npmtest/node-npmtest-oracledb)

#### Oracle Database driver by Oracle Corp.

[![NPM](https://nodei.co/npm/oracledb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/oracledb)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-oracledb/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-oracledb/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-oracledb/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-oracledb/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-oracledb/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-oracledb/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-oracledb/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-oracledb/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-oracledb/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-oracledb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-oracledb/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-oracledb/build/test-report.html](https://npmtest.github.io/node-npmtest-oracledb/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-oracledb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-oracledb/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-oracledb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-oracledb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-oracledb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-oracledb/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-oracledb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-oracledb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "oracledb",
    "version": "1.13.1",
    "description": "Oracle Database driver by Oracle Corp.",
    "license": "Apache-2.0",
    "homepage": "http://www.oracle.com/technetwork/database/database-technologies/scripting-languages/node_js/",
    "keywords": [
        "Oracle",
        "Database",
        "official",
        "DB",
        "SQL",
        "JSON",
        "PL/SQL",
        "OCI",
        "API",
        "client",
        "library",
        "driver",
        "add-on",
        "extension",
        "binding",
        "interface",
        "adapter",
        "module"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/oracle/node-oracledb.git"
    },
    "dependencies": {
        "nan": "~2.5.0"
    },
    "devDependencies": {
        "mocha": "^2.4.5",
        "should": "^8.3.1",
        "async": "^1.5.0"
    },
    "scripts": {
        "test": "mocha --opts test/opts/mocha.opts",
        "posttest": "node test/opts/versions.js",
        "testwindows": "mocha --opts test\\opts\\mocha.opts && npm run posttest"
    },
    "engines": {
        "node": ">=0.10.28"
    },
    "maintainers": [
        {
            "name": "Oracle Corp."
        }
    ],
    "bugs": {
        "url": "https://github.com/oracle/node-oracledb/issues"
    },
    "main": "./index.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
