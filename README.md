# npmtest-custom-react-scripts

#### basic test coverage for  custom-react-scripts (v0.0.23)  [![npm package](https://img.shields.io/npm/v/npmtest-custom-react-scripts.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-custom-react-scripts) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-custom-react-scripts.svg)](https://travis-ci.org/npmtest/node-npmtest-custom-react-scripts)

#### Configuration and scripts for Create React App.

[![NPM](https://nodei.co/npm/custom-react-scripts.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/custom-react-scripts)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-custom-react-scripts/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-custom-react-scripts/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-custom-react-scripts/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-custom-react-scripts/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-custom-react-scripts/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-custom-react-scripts/build/test-report.html](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-custom-react-scripts/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-custom-react-scripts/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-custom-react-scripts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-custom-react-scripts/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-custom-react-scripts/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "react-scripts": "./bin/react-scripts.js"
    },
    "bugs": {
        "url": "https://github.com/kitze/create-react-app/issues"
    },
    "dependencies": {
        "autoprefixer": "6.5.1",
        "babel-core": "6.17.0",
        "babel-eslint": "7.1.1",
        "babel-jest": "18.0.0",
        "babel-loader": "6.2.10",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-preset-react-app": "^2.0.1",
        "babel-preset-stage-0": "^6.5.0",
        "babel-runtime": "^6.20.0",
        "case-sensitive-paths-webpack-plugin": "1.1.4",
        "chalk": "1.1.3",
        "connect-history-api-fallback": "1.3.0",
        "cross-spawn": "4.0.2",
        "css-loader": "0.26.0",
        "detect-port": "1.0.1",
        "dotenv": "2.0.0",
        "eslint": "3.8.1",
        "eslint-config-react-app": "^0.5.0",
        "eslint-loader": "1.6.0",
        "eslint-plugin-flowtype": "2.21.0",
        "eslint-plugin-import": "2.0.1",
        "eslint-plugin-jsx-a11y": "2.2.3",
        "eslint-plugin-react": "6.4.1",
        "extract-text-webpack-plugin": "1.0.1",
        "file-loader": "0.9.0",
        "filesize": "3.3.0",
        "fs-extra": "0.30.0",
        "fsevents": "1.0.14",
        "gzip-size": "3.0.0",
        "html-webpack-plugin": "2.24.0",
        "http-proxy-middleware": "0.17.2",
        "jest": "18.1.0",
        "json-loader": "0.5.4",
        "less": "^2.7.1",
        "less-loader": "^2.2.3",
        "node-sass": "^3.10.0",
        "object-assign": "4.1.0",
        "postcss-loader": "1.0.0",
        "promise": "7.1.1",
        "react-dev-utils": "^0.4.2",
        "recursive-readdir": "2.1.0",
        "rimraf": "2.5.4",
        "sass-loader": "^4.0.2",
        "strip-ansi": "3.0.1",
        "style-loader": "0.13.1",
        "stylus": "^0.54.5",
        "stylus-loader": "^2.3.1",
        "url-loader": "0.5.7",
        "webpack": "1.14.0",
        "webpack-dev-server": "1.16.2",
        "webpack-manifest-plugin": "1.1.0",
        "whatwg-fetch": "1.0.0"
    },
    "description": "Configuration and scripts for Create React App.",
    "devDependencies": {
        "react": "^15.3.0",
        "react-dom": "^15.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8161cf23fc155f663df9df1485623f59b9822b1a",
        "tarball": "https://registry.npmjs.org/custom-react-scripts/-/custom-react-scripts-0.0.23.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        ".babelrc",
        ".eslintrc",
        "bin",
        "config",
        "scripts",
        "template",
        "utils"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "kitze"
        }
    ],
    "name": "custom-react-scripts",
    "optionalDependencies": {
        "fsevents": "1.0.14"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/kitze/create-react-app/"
    },
    "scripts": {},
    "version": "0.0.23"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
