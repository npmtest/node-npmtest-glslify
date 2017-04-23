# npmtest-glslify

#### basic test coverage for  [glslify (v6.0.2)](https://github.com/stackgl/glslify)  [![npm package](https://img.shields.io/npm/v/npmtest-glslify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-glslify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-glslify.svg)](https://travis-ci.org/npmtest/node-npmtest-glslify)

#### A node.js-style module system for GLSL!

[![NPM](https://nodei.co/npm/glslify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/glslify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-glslify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-glslify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-glslify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-glslify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-glslify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-glslify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-glslify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-glslify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-glslify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-glslify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-glslify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-glslify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-glslify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-glslify/build/test-report.html](https://npmtest.github.io/node-npmtest-glslify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-glslify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-glslify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-glslify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-glslify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-glslify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-glslify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-glslify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-glslify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Hugh Kennedy <hughskennedy@gmail.com> (http://hughsk.io/)",
        "Mikola Lysenko <mikolalysenko@gmail.com> (http://0fps.net)",
        "Chris Dickinson <chris@neversaw.us> (http://neversaw.us)"
    ],
    "bin": {
        "glslify": "bin.js"
    },
    "browser": {
        "index.js": "./browser.js"
    },
    "bugs": {
        "url": "https://github.com/stackgl/glslify/issues"
    },
    "dependencies": {
        "bl": "^1.0.0",
        "concat-stream": "^1.5.2",
        "duplexify": "^3.4.5",
        "falafel": "^2.0.0",
        "from2": "^2.3.0",
        "glsl-resolve": "0.0.1",
        "glsl-token-whitespace-trim": "^1.0.0",
        "glslify-bundle": "^5.0.0",
        "glslify-deps": "^1.2.5",
        "minimist": "^1.2.0",
        "resolve": "^1.1.5",
        "stack-trace": "0.0.9",
        "static-eval": "^1.1.1",
        "tape": "^4.6.0",
        "through2": "^2.0.1",
        "xtend": "^4.0.0"
    },
    "description": "A node.js-style module system for GLSL!",
    "devDependencies": {
        "browserify": "^12.0.1",
        "electron-prebuilt": "^1.3.3",
        "electron-spawn": "^5.0.0",
        "from2": "^2.3.0",
        "glsl-easings": "^1.0.0",
        "glsl-noise": "0.0.0",
        "glslify-hex": "^2.0.1",
        "shell-quote": "^1.4.3",
        "tap-spec": "^2.2.1",
        "tape": "^3.5.0",
        "uniq": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "9312362ff69ba2b818cf89eaf1618fa2a342cef8",
        "tarball": "https://registry.npmjs.org/glslify/-/glslify-6.0.2.tgz"
    },
    "gitHead": "e0f5e5aecfd31c1741d91384ba049670ebb40ee9",
    "homepage": "https://github.com/stackgl/glslify",
    "keywords": [
        "ecosystem:stackgl",
        "browserify-transform",
        "glslify",
        "glsl",
        "module",
        "system",
        "cli",
        "shader",
        "webgl"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "chrisdickinson"
        },
        {
            "name": "hughsk"
        },
        {
            "name": "mattdesl"
        },
        {
            "name": "mikkoh"
        },
        {
            "name": "mikolalysenko"
        },
        {
            "name": "rezaali"
        },
        {
            "name": "substack"
        },
        {
            "name": "tatumcreative"
        },
        {
            "name": "thibauts"
        },
        {
            "name": "wwwtyro"
        },
        {
            "name": "yoshuawuyts"
        }
    ],
    "name": "glslify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/stackgl/glslify.git"
    },
    "scripts": {
        "test": "npm run test-node && npm run test-electron",
        "test-electron": "test/electron.sh",
        "test-node": "node test | tap-spec"
    },
    "version": "6.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
