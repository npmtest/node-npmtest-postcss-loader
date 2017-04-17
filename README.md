# test coverage for  [postcss-loader (v1.3.3)](https://github.com/postcss/postcss-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-loader)
#### PostCSS loader for webpack

[![NPM](https://nodei.co/npm/postcss-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrey Sitnik"
    },
    "bugs": {
        "url": "https://github.com/postcss/postcss-loader/issues"
    },
    "dependencies": {
        "loader-utils": "^1.0.2",
        "object-assign": "^4.1.1",
        "postcss": "^5.2.15",
        "postcss-load-config": "^1.2.0"
    },
    "description": "PostCSS loader for webpack",
    "devDependencies": {
        "eslint": "^3.16.1",
        "eslint-config-postcss": "^2.0.2",
        "fs-extra": "^2.0.0",
        "gulp": "^3.9.1",
        "gulp-eslint": "^3.0.1",
        "gulp-jest": "^1.0.0",
        "jest-cli": "^19.0.2",
        "json-loader": "^0.5.4",
        "lint-staged": "^3.3.1",
        "postcss-js": "^0.3.0",
        "postcss-safe-parser": "^2.0.0",
        "pre-commit": "^1.2.2",
        "raw-loader": "^0.5.1",
        "sugarss": "^0.2.0",
        "webpack-stream": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a621ea1fa29062a83972a46f54486771301916eb",
        "tarball": "https://registry.npmjs.org/postcss-loader/-/postcss-loader-1.3.3.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "eslintConfig": {
        "extends": "eslint-config-postcss/es5",
        "env": {
            "jest": true
        }
    },
    "gitHead": "e101b845eaa8e7ad006e9a8294c3d64b9061b86c",
    "homepage": "https://github.com/postcss/postcss-loader#readme",
    "keywords": [
        "webpack",
        "loader",
        "css",
        "postcss",
        "postcss-runner"
    ],
    "license": "MIT",
    "lint-staged": {
        "*.js": "eslint"
    },
    "maintainers": [
        {
            "name": "ai"
        }
    ],
    "name": "postcss-loader",
    "optionalDependencies": {},
    "pre-commit": [
        "lint-staged"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/postcss/postcss-loader.git"
    },
    "scripts": {
        "lint-staged": "lint-staged",
        "test": "gulp"
    },
    "version": "1.3.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
