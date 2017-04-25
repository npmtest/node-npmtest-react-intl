# npmtest-react-intl

#### basic test coverage for  [react-intl (v2.2.3)](https://github.com/yahoo/react-intl)  [![npm package](https://img.shields.io/npm/v/npmtest-react-intl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-intl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-intl.svg)](https://travis-ci.org/npmtest/node-npmtest-react-intl)

#### Internationalize React apps. This library provides React components and an API to format dates, numbers, and strings, including pluralization and handling translations.

[![NPM](https://nodei.co/npm/react-intl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-intl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-intl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-intl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-intl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-intl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-intl/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-intl/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-intl/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-intl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-intl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-intl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-intl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-intl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-intl/build/test-report.html](https://npmtest.github.io/node-npmtest-react-intl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-intl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-intl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-intl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-intl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-intl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-intl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Ferraiuolo"
    },
    "browser": {
        "./locale-data/index": false,
        "./locale-data/index.js": false
    },
    "browserify-shim": {
        "react": "global:React"
    },
    "bugs": {
        "url": "https://github.com/yahoo/react-intl/issues"
    },
    "contributors": [
        {
            "name": "Caridy Patino"
        }
    ],
    "dependencies": {
        "intl-format-cache": "^2.0.5",
        "intl-messageformat": "^1.3.0",
        "intl-relativeformat": "^1.3.0",
        "invariant": "^2.1.1"
    },
    "description": "Internationalize React apps. This library provides React components and an API to format dates, numbers, and strings, including pluralization and handling translations.",
    "devDependencies": {
        "babel-cli": "^6.2.0",
        "babel-eslint": "^7.1.1",
        "babel-jest": "^18.0.0",
        "babel-plugin-external-helpers": "^6.18.0",
        "babel-plugin-react-intl": "^2.0.0",
        "babel-plugin-transform-class-properties": "^6.11.5",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.18.0",
        "babel-plugin-transform-es3-member-expression-literals": "^6.3.13",
        "babel-plugin-transform-es3-property-literals": "^6.3.13",
        "babel-plugin-transform-object-rest-spread": "^6.1.18",
        "babel-plugin-transform-react-remove-prop-types": "^0.2.10",
        "babel-preset-es2015": "^6.1.18",
        "babel-preset-react": "^6.1.18",
        "babelify": "^7.2.0",
        "benchmark": "^2.1.0",
        "browserify": "^13.0.0",
        "browserify-shim": "^3.8.11",
        "cross-env": "^3.1.3",
        "eslint": "^3.10.2",
        "eslint-plugin-react": "^6.2.0",
        "expect": "^1.9.0",
        "expect-jsx": "^3.0.0",
        "express": "^4.13.3",
        "formatjs-extract-cldr-data": "^2.0.0",
        "glob": "^7.0.0",
        "intl": "^1.2.1",
        "intl-messageformat-parser": "^1.2.0",
        "jest": "^18.0.0",
        "mkdirp": "^0.5.1",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "rimraf": "^2.4.2",
        "rollup": "^0.41.4",
        "rollup-plugin-babel": "^2.3.9",
        "rollup-plugin-commonjs": "^7.0.0",
        "rollup-plugin-memory": "^2.0.0",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rollup-plugin-replace": "^1.1.0",
        "rollup-plugin-uglify": "^1.0.0",
        "serialize-javascript": "^1.1.1",
        "superagent": "^3.0.0",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8eebb03cddc38b337ed22fab78037ab53a594270",
        "tarball": "https://registry.npmjs.org/react-intl/-/react-intl-2.2.3.tgz"
    },
    "gitHead": "cc9ecff1405e8bc3149a829da776b061ecb08300",
    "homepage": "https://github.com/yahoo/react-intl",
    "jest": {
        "testRegex": "/test/(unit|functional)/.*\\.js",
        "testPathIgnorePatterns": [
            "/test/functional/support/"
        ],
        "collectCoverageFrom": [
            "src/**/*.js",
            "!src/en.js"
        ],
        "coverageReporters": [
            "lcov",
            "text",
            "text-summary",
            "html"
        ],
        "coverageThreshold": {
            "global": {
                "branches": 85,
                "functions": 100,
                "lines": 95,
                "statements": 95
            }
        }
    },
    "jsnext:main": "./lib/index.es.js",
    "keywords": [
        "intl",
        "i18n",
        "internationalization",
        "locale",
        "localization",
        "globalization",
        "react",
        "reactjs",
        "format",
        "formatting",
        "translate",
        "translation"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "caridy"
        },
        {
            "name": "juandopazo"
        },
        {
            "name": "ericf"
        },
        {
            "name": "clarle"
        }
    ],
    "module": "./lib/index.es.js",
    "name": "react-intl",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yahoo/react-intl.git"
    },
    "scripts": {
        "build": "npm run build:data && npm run build:lib && npm run build:dist",
        "build:data": "babel-node scripts/build-data",
        "build:dist": "npm run build:dist:dev && npm run build:dist:prod",
        "build:dist:dev": "cross-env NODE_ENV=development rollup -c rollup.config.dist.js",
        "build:dist:prod": "cross-env NODE_ENV=production rollup -c rollup.config.dist.js",
        "build:lib": "rollup -c rollup.config.lib.js",
        "clean": "rimraf src/en.js coverage/ dist/ lib/ locale-data/",
        "examples:install": "babel-node scripts/examples npm install",
        "examples:link": "npm link && babel-node scripts/examples npm link react-intl",
        "lint": "eslint .",
        "lint:fix": "eslint . --fix",
        "prepublish": "npm run clean && npm run build",
        "preversion": "npm run clean && npm run build && npm run test:all",
        "react:14": "npm run react:clean && npm i react@^0.14 react-dom@^0.14 react-addons-test-utils@^0.14",
        "react:15": "npm run react:clean && npm i react@^15 react-dom@^15 react-addons-test-utils@^15",
        "react:clean": "rimraf node_modules/{react,react-dom,react-addons-test-utils}",
        "test": "jest --coverage --verbose",
        "test:all": "npm run lint && npm run test && npm run test:react",
        "test:perf": "cross-env NODE_ENV=production babel-node test/perf",
        "test:react": "npm run react:14 && jest && npm run react:15 && jest",
        "test:watch": "jest --watch"
    },
    "version": "2.2.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
