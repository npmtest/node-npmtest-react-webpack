# npmtest-react-webpack

#### test coverage for  [react-webpack (v0.4.1)](https://github.com/ThomasDeutsch/react-webpack)  [![npm package](https://img.shields.io/npm/v/npmtest-react-webpack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-webpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-webpack.svg)](https://travis-ci.org/npmtest/node-npmtest-react-webpack)

#### React + Webpack Starter Template

[![NPM](https://nodei.co/npm/react-webpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-webpack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-webpack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-webpack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-webpack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-webpack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-webpack/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-webpack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-webpack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-webpack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-webpack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-webpack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-webpack/build/test-report.html](https://npmtest.github.io/node-npmtest-react-webpack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-webpack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-webpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-webpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-webpack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-webpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-webpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thomas Deutsch"
    },
    "bugs": {
        "url": "https://github.com/ThomasDeutsch/react-webpack/issues"
    },
    "dependencies": {
        "css-loader": "~0.6.8",
        "envify": "~1.2.1",
        "jsx-loader": "~0.9.0",
        "less-loader": "~0.7.1",
        "react": "~0.9.0",
        "script-loader": "~0.5.2",
        "style-loader": "~0.6.2",
        "webpack": "~1.0.1"
    },
    "description": "React + Webpack Starter Template",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "07c6f7d74528af9cd82aac3e2df51e1cb7264958",
        "tarball": "https://registry.npmjs.org/react-webpack/-/react-webpack-0.4.1.tgz"
    },
    "files": [
        "devserver/",
        "source/",
        "build/",
        "server.config",
        "webpack.config"
    ],
    "homepage": "https://github.com/ThomasDeutsch/react-webpack",
    "keywords": [
        "webpack",
        "react"
    ],
    "license": "ISC",
    "maintainers": [
        {
            "name": "thomas-deutsch"
        }
    ],
    "name": "react-webpack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ThomasDeutsch/react-webpack.git"
    },
    "scripts": {
        "devserver": "webpack-dev-server --config server.config.js --content-base ./devserver_files --port 9500 --colors",
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "0.4.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
