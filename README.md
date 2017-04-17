# test coverage for  [sql-cli (v0.5.2)](https://github.com/hasankhan/sql-cli)  [![npm package](https://img.shields.io/npm/v/npmtest-sql-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sql-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sql-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-sql-cli)
#### Cross platform command line interface for SQL Server

[![NPM](https://nodei.co/npm/sql-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sql-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sql-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sql-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sql-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sql-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sql-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sql-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sql-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sql-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sql-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sql-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sql-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sql-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-sql-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sql-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sql-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sql-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sql-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sql-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sql-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sql-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sql-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Muhammad Hasan Khan"
    },
    "bin": {
        "mssql": "./bin/mssql"
    },
    "bugs": {
        "url": "https://github.com/hasankhan/sql-cli/issues"
    },
    "dependencies": {
        "chardet": "^0.1.0",
        "commander": "^2.9.0",
        "easy-table": "^1.0.0",
        "iconv-lite": "^0.4.13",
        "mssql": "^3.3.0",
        "mstring": "^0.1.2",
        "password-prompt": "^1.0.2",
        "q": "^2.0.3",
        "sprintf-js": "^1.0.3",
        "underscore": "^1.8.3",
        "underscore.string": "^3.3.4",
        "ya-csv": "^0.9.4"
    },
    "description": "Cross platform command line interface for SQL Server",
    "devDependencies": {
        "crlf": "^1.1.0",
        "jasmine-node": "~1.14.3",
        "jshint": "~2.5.1",
        "proxyquire": "~1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d2fde54d6e49d08e9abaa31604102596c8b47125",
        "tarball": "https://registry.npmjs.org/sql-cli/-/sql-cli-0.5.2.tgz"
    },
    "engines": {
        "node": ">= 4.6"
    },
    "gitHead": "78feb435527cbd89463abd4ba4a676559b8d38e5",
    "homepage": "https://github.com/hasankhan/sql-cli",
    "keywords": [
        "node",
        "azure",
        "cli",
        "sql"
    ],
    "licenses": [
        {
            "type": "Apache",
            "url": "http://www.apache.org/licenses/LICENSE-2.0"
        }
    ],
    "main": "./lib/cli.js",
    "maintainers": [
        {
            "name": "hasankhan"
        }
    ],
    "name": "sql-cli",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/hasankhan/sql-cli.git"
    },
    "scripts": {
        "jshint": "jshint lib",
        "prepublishOnly": "crlf --set=LF bin/mssql",
        "test": "npm -s run-script jshint && npm -s run-script unit",
        "unit": "jasmine-node test"
    },
    "tags": [
        "sql",
        "cli"
    ],
    "version": "0.5.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
