# npmdoc-browserslist

#### basic api documentation for  [browserslist (v2.1.0)](https://github.com/ai/browserslist#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-browserslist.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-browserslist) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-browserslist.svg)](https://travis-ci.org/npmdoc/node-npmdoc-browserslist)

#### Share browsers list between different front-end tools, like Autoprefixer, Stylelint and babel-env-preset

[![NPM](https://nodei.co/npm/browserslist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browserslist)

- [https://npmdoc.github.io/node-npmdoc-browserslist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browserslist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browserslist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browserslist/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-browserslist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-browserslist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrey Sitnik"
    },
    "bin": {
        "browserslist": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/ai/browserslist/issues"
    },
    "dependencies": {
        "caniuse-lite": "^1.0.30000659",
        "electron-to-chromium": "^1.3.8"
    },
    "description": "Share browsers list between different front-end tools, like Autoprefixer, Stylelint and babel-env-preset",
    "devDependencies": {
        "cross-spawn": "^5.1.0",
        "eslint": "^3.19.0",
        "eslint-config-postcss": "^2.0.2",
        "jest": "^19.0.2",
        "lint-staged": "^3.4.0",
        "pre-commit": "^1.1.3",
        "yaspeller-ci": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2590d3de07c7129a7bd05ce3c3cb2a3fc56e78fa",
        "tarball": "https://registry.npmjs.org/browserslist/-/browserslist-2.1.0.tgz"
    },
    "eslintConfig": {
        "extends": "eslint-config-postcss/es5",
        "env": {
            "jest": true
        },
        "rules": {
            "consistent-return": "off",
            "no-process-exit": "off",
            "valid-jsdoc": "error"
        }
    },
    "gitHead": "a69344d4d1e725827dc52dd8299526be6fc39a73",
    "homepage": "https://github.com/ai/browserslist#readme",
    "jest": {
        "coverageThreshold": {
            "global": {
                "statements": 100
            }
        }
    },
    "keywords": [
        "caniuse",
        "browsers"
    ],
    "license": "MIT",
    "lint-staged": {
        "*.md": "yaspeller-ci",
        "*.js": "eslint"
    },
    "maintainers": [
        {
            "name": "ai"
        }
    ],
    "name": "browserslist",
    "optionalDependencies": {},
    "pre-commit": [
        "lint-staged"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ai/browserslist.git"
    },
    "scripts": {
        "lint-staged": "lint-staged",
        "spellcheck": "yaspeller-ci README.md CHANGELOG.md",
        "test": "jest --coverage && eslint *.js test/*.js && yarn run spellcheck"
    },
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
