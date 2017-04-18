# npmtest-eslint-plugin-lodash-fp

#### test coverage for  [eslint-plugin-lodash-fp (v2.1.3)](https://github.com/jfmengels/eslint-plugin-lodash-fp#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-lodash-fp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-lodash-fp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-lodash-fp.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-lodash-fp)

#### ESLint rules for lodash/fp

[![NPM](https://nodei.co/npm/eslint-plugin-lodash-fp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-lodash-fp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-lodash-fp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-lodash-fp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash-fp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash-fp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash-fp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-lodash-fp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-lodash-fp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeroen Engels",
        "url": "github.com/jfmengels"
    },
    "bugs": {
        "url": "https://github.com/jfmengels/eslint-plugin-lodash-fp/issues"
    },
    "dependencies": {
        "create-eslint-index": "^1.0.0",
        "enhance-visitors": "^1.0.0",
        "eslint-ast-utils": "^1.0.0",
        "lodash": "^4.11.1",
        "req-all": "^0.1.0"
    },
    "description": "ESLint rules for lodash/fp",
    "devDependencies": {
        "ava": "^0.16.0",
        "eslint": "^3.0.1",
        "eslint-ava-rule-tester": "^2.0.0",
        "inject-in-tag": "^1.1.1",
        "nyc": "^6.4.0",
        "pify": "^2.3.0",
        "xo": "^0.17.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ec1d6782abb834415334b97a20b145730a0d0a78",
        "tarball": "https://registry.npmjs.org/eslint-plugin-lodash-fp/-/eslint-plugin-lodash-fp-2.1.3.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "index.js",
        "rules"
    ],
    "gitHead": "e344a9f7633d4dd19afd1d091f959bd45a339766",
    "homepage": "https://github.com/jfmengels/eslint-plugin-lodash-fp#readme",
    "keywords": [
        "eslint",
        "plugin",
        "eslint-plugin",
        "eslintplugin",
        "lodash",
        "lodash/fp",
        "lodash-fp",
        "fp",
        "FP",
        "functional",
        "programming"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jfmengels"
        }
    ],
    "name": "eslint-plugin-lodash-fp",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": ">=3"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jfmengels/eslint-plugin-lodash-fp.git"
    },
    "scripts": {
        "test": "xo && nyc ava",
        "update-md": "inject-in-tag ./rule-description.js readme.md"
    },
    "version": "2.1.3",
    "xo": {
        "exnext": true,
        "space": 2
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
