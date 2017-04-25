# npmdoc-gulp-stylelint

#### basic api documentation for  [gulp-stylelint (v3.9.0)](https://github.com/olegskl/gulp-stylelint)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-stylelint.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-stylelint) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-stylelint.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-stylelint)

#### Gulp plugin for running Stylelint results through various reporters.

[![NPM](https://nodei.co/npm/gulp-stylelint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-stylelint)

- [https://npmdoc.github.io/node-npmdoc-gulp-stylelint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-stylelint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-stylelint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-stylelint/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-stylelint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-stylelint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Oleg Sklyanchuk",
        "url": "http://olegskl.com"
    },
    "bugs": {
        "url": "https://github.com/olegskl/gulp-stylelint/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "deep-extend": "^0.4.1",
        "gulp-util": "^3.0.8",
        "mkdirp": "^0.5.1",
        "promise": "^7.1.1",
        "stylelint": "^7.9.0",
        "through2": "^2.0.3"
    },
    "description": "Gulp plugin for running Stylelint results through various reporters.",
    "devDependencies": {
        "babel-cli": "^6.23.0",
        "babel-core": "^6.23.1",
        "babel-preset-es2015": "^6.22.0",
        "babel-register": "^6.23.0",
        "eslint": "^3.16.0",
        "eslint-config-meetic": "^4.0.0",
        "gulp": "^3.9.1",
        "sinon": "^1.17.7",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "a09a67af490b1fb28eb910b4cbfb5412c7f0bb71",
        "tarball": "https://registry.npmjs.org/gulp-stylelint/-/gulp-stylelint-3.9.0.tgz"
    },
    "gitHead": "02f66c92c3ffd1e57906c02263c28fa3ba728467",
    "homepage": "https://github.com/olegskl/gulp-stylelint",
    "keywords": [
        "gulpplugin",
        "stylelint",
        "postcss",
        "css"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "olegskl"
        }
    ],
    "name": "gulp-stylelint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/olegskl/gulp-stylelint.git"
    },
    "scripts": {
        "lint": "eslint src/**/*.js",
        "prepublish": "npm run lint && npm test && npm run transpile",
        "test": "tape -r babel-register test/*.spec.js",
        "transpile": "babel src --out-dir dist"
    },
    "version": "3.9.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
