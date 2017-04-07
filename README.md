# api documentation for  [oboe (v2.1.3)](http://oboejs.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-oboe.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-oboe) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-oboe.svg)](https://travis-ci.org/npmdoc/node-npmdoc-oboe)
#### Oboe.js reads json, giving you the objects as they are found without waiting for the stream to finish

[![NPM](https://nodei.co/npm/oboe.png?downloads=true)](https://www.npmjs.com/package/oboe)

[![apidoc](https://npmdoc.github.io/node-npmdoc-oboe/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-oboe_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-oboe/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-oboe/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-oboe/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jim Higson"
    },
    "browser": "./dist/oboe-browser.js",
    "bugs": {
        "url": "https://github.com/jimhigson/oboe.js/issues"
    },
    "dependencies": {
        "http-https": "^1.0.0"
    },
    "description": "Oboe.js reads json, giving you the objects as they are found without waiting for the stream to finish",
    "devDependencies": {
        "color": "~0.4.4",
        "cors": "~2.1.1",
        "doctoc": "~0.4.3",
        "express": "~3.4.3",
        "get-json": "0.0.1",
        "grunt": "~0.4.1",
        "grunt-clear": "~0.2.1",
        "grunt-cli": "~0.1.9",
        "grunt-concurrent": "~0.3.1",
        "grunt-contrib-clean": "~0.5.0",
        "grunt-contrib-concat": "~0.1.3",
        "grunt-contrib-copy": "~0.4.1",
        "grunt-contrib-uglify": "~0.2.0",
        "grunt-contrib-watch": "~0.5.1",
        "grunt-exec": "~0.4.2",
        "grunt-karma": "~0.6.2",
        "grunt-micro": "~0.1.0",
        "grunt-wrap": "~0.2.0",
        "jasmine-node": "~1.11.0",
        "karma": "~0.10.0",
        "karma-coverage": "^0.2.4",
        "karma-firefox-launcher": "~0.1.0",
        "karma-jasmine": "~0.1.5",
        "karma-safari-launcher": "~0.1.1",
        "matchdep": "~0.1.2",
        "request": "^2.55.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2b4865dbd46be81225713f4e9bfe4bcf4f680a4f",
        "tarball": "https://registry.npmjs.org/oboe/-/oboe-2.1.3.tgz"
    },
    "gitHead": "537e9e75b61f75d2d402632505ff3c9a12dd254f",
    "homepage": "http://oboejs.com",
    "jam": {
        "main": "dist/oboe-browser.js",
        "include": [
            "dist/oboe-browser.js",
            "LICENCE",
            "package.json",
            "README.md"
        ],
        "dependencies": {},
        "categories": [
            "AJAX & Websockets",
            "Parsers & Compilers"
        ]
    },
    "keywords": [
        "json",
        "parser",
        "stream",
        "progressive",
        "http",
        "sax",
        "event",
        "emitter",
        "async",
        "browser"
    ],
    "license": "BSD",
    "main": "./dist/oboe-node.js",
    "maintainers": [
        {
            "name": "jimhigson",
            "email": "jim.higson@gmail.com"
        },
        {
            "name": "joombar",
            "email": "jim.higson@gmail.com"
        },
        {
            "name": "juancaicedo",
            "email": "retiredcanadianpoet@gmail.com"
        }
    ],
    "name": "oboe",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jimhigson/oboe.js.git"
    },
    "scripts": {
        "browser-test-auto-run": "node ./node_modules/grunt-cli/bin/grunt test-auto-run",
        "dist-sizes": "node ./node_modules/grunt-cli/bin/grunt dist-sizes",
        "node-test-auto-run": "node ./node_modules/grunt-cli/bin/grunt node-test-auto-run",
        "test": "node ./node_modules/grunt-cli/bin/grunt headless-mode default",
        "test-run": "node ./node_modules/grunt-cli/bin/grunt test-run",
        "test-start-server": "node ./node_modules/grunt-cli/bin/grunt test-start-server"
    },
    "title": "Oboe.js",
    "version": "2.1.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module oboe](#apidoc.module.oboe)
1.  [function <span class="apidocSignatureSpan">oboe.</span>drop ()](#apidoc.element.oboe.drop)



# <a name="apidoc.module.oboe"></a>[module oboe](#apidoc.module.oboe)

#### <a name="apidoc.element.oboe.drop"></a>[function <span class="apidocSignatureSpan">oboe.</span>drop ()](#apidoc.element.oboe.drop)
- description and source-code
```javascript
drop = function () {
   return oboe.drop;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
