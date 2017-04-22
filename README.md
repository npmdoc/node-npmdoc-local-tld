# npmdoc-local-tld

#### api documentation for  local-tld (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-local-tld.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-local-tld) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-local-tld.svg)](https://travis-ci.org/npmdoc/node-npmdoc-local-tld)

#### Maintain a TLD on localhost for all your projects.

[![NPM](https://nodei.co/npm/local-tld.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/local-tld)

- [https://npmdoc.github.io/node-npmdoc-local-tld/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-local-tld/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-local-tld/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-local-tld/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-local-tld/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-local-tld/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "local-tld",
    "version": "4.0.0",
    "description": "Maintain a TLD on localhost for all your projects.",
    "main": "bin/local-tld-service",
    "dependencies": {
        "dnsserver": "https://github.com/sstephenson/dnsserver.js/archive/library.tar.gz",
        "watchfd": "~0.0.9",
        "http-proxy": "~0.8.7"
    },
    "devDependencies": {},
    "scripts": {
        "postinstall": "./bin/local-tld-setup",
        "preuninstall": "./bin/local-tld-uninstall"
    },
    "repository": "https://github.com:hoodiehq/local-tld",
    "keywords": [
        "tld",
        "pow"
    ],
    "os": [
        "darwin"
    ],
    "author": "Jan Lehnardt <jan@apache.org>",
    "license": "Apache 2.0",
    "readmeFilename": "README.md",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
