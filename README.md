# npmdoc-postcss-modules

#### api documentation for  postcss-modules (v0.6.4)  [![npm package](https://img.shields.io/npm/v/npmdoc-postcss-modules.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-postcss-modules) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-postcss-modules.svg)](https://travis-ci.org/npmdoc/node-npmdoc-postcss-modules)

#### PostCSS plugin to use CSS Modules everywhere

[![NPM](https://nodei.co/npm/postcss-modules.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-modules)

- [https://npmdoc.github.io/node-npmdoc-postcss-modules/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "postcss-modules",
    "version": "0.6.4",
    "description": "PostCSS plugin to use CSS Modules everywhere",
    "main": "build/index.js",
    "keywords": [
        "postcss",
        "css",
        "postcss-plugin",
        "modules",
        "css modules",
        "components"
    ],
    "author": "Alexander Madyankin <alexander@madyankin.name>",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/css-modules/postcss-modules.git"
    },
    "dependencies": {
        "css-modules-loader-core": "^1.0.1",
        "generic-names": "^1.0.2",
        "postcss": "^5.2.8",
        "string-hash": "^1.1.1"
    },
    "devDependencies": {
        "autoprefixer": "^6.6.0",
        "ava": "^0.17.0",
        "babel": "^6.5.2",
        "babel-cli": "^6.18.0",
        "babel-core": "^6.21.0",
        "babel-eslint": "^7.1.1",
        "babel-preset-es2015": "^6.18.0",
        "eslint": "^3.12.2",
        "eslint-config-airbnb-base": "^11.0.0",
        "eslint-plugin-import": "^2.2.0",
        "file-exists": "^2.0.0"
    },
    "scripts": {
        "pretest": "$(npm bin)/eslint src test",
        "test": "$(npm bin)/babel-node $(npm bin)/ava",
        "transpile": "$(npm bin)/babel src -d build",
        "prepublish": "npm run transpile",
        "postpublish": "rm -rf build && git push --follow-tags"
    },
    "require": "babel-core/register"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
