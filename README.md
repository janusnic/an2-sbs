# an2-sbs

# nvm use 6.5
    Now using node v6.5.0 (npm v3.10.3)

# git clone https://github.com/janusnic/an2-sbs

# git init

# npm init
        This utility will walk you through creating a package.json file.
        It only covers the most common items, and tries to guess sensible defaults.

        See `npm help json` for definitive documentation on these fields
        and exactly what they do.

        Use `npm install <pkg> --save` afterwards to install a package and
        save it as a dependency in the package.json file.

        Press ^C at any time to quit.
        name: (an2-sbs)
        version: (1.0.0)
        description: Ahgular 2 Step by step project
        entry point: (index.js)
        test command:
        git repository: (https://github.com/janusnic/an2-sbs)
        keywords: ahgular2 typeScript nodejs
        author: Janus Nicon
        license: (ISC) MIT
        About to write to /home/janus/github/an2-sbs/package.json:

        {
          "name": "an2-sbs",
          "version": "1.0.0",
          "description": "Ahgular 2 Step by step project",
          "main": "index.js",
          "scripts": {
            "test": "echo \"Error: no test specified\" && exit 1"
          },
          "repository": {
            "type": "git",
            "url": "git+https://github.com/janusnic/an2-sbs.git"
          },
          "keywords": [
            "ahgular2",
            "typeScript",
            "nodejs"
          ],
          "author": "Janus Nicon",
          "license": "MIT",
          "bugs": {
            "url": "https://github.com/janusnic/an2-sbs/issues"
          },
          "homepage": "https://github.com/janusnic/an2-sbs#readme"
        }

        Is this ok? (yes) yes

# create-and-configure
https://angular.io/docs/ts/latest/quickstart.html#!#create-and-configure

# package.json:
        {
          "name": "an2-sbs",
          "version": "1.0.0",
          "description": "Ahgular 2 Step by step project",
          "scripts": {
              "start": "tsc && concurrently \"npm run tsc:w\" \"npm run lite\" ",
              "lite": "lite-server",
              "postinstall": "typings install",
              "tsc": "tsc",
              "tsc:w": "tsc -w",
              "typings": "typings",
              "test": "echo \"Error: no test specified\" && exit 1"
          },
          "dependencies": {
            "@angular/common": "2.0.0-rc.6",
            "@angular/compiler": "2.0.0-rc.6",
            "@angular/compiler-cli": "0.6.0",
            "@angular/core": "2.0.0-rc.6",
            "@angular/forms": "2.0.0-rc.6",
            "@angular/http": "2.0.0-rc.6",
            "@angular/platform-browser": "2.0.0-rc.6",
            "@angular/platform-browser-dynamic": "2.0.0-rc.6",
            "@angular/router": "3.0.0-rc.2",
            "@angular/upgrade": "2.0.0-rc.6",
            "core-js": "^2.4.1",
            "reflect-metadata": "^0.1.3",
            "rxjs": "5.0.0-beta.11",
            "systemjs": "0.19.27",
            "zone.js": "^0.6.17",
            "angular2-in-memory-web-api": "0.0.18",
            "bootstrap": "^3.3.6"
          },
          "devDependencies": {
            "concurrently": "^2.2.0",
            "lite-server": "^2.2.2",
            "typescript": "^1.8.10",
            "typings":"^1.3.2"
          },
          "repository": {
            "type": "git",
            "url": "git+https://github.com/janusnic/an2-sbs.git"
          },
          "keywords": [
            "ahgular2",
            "typeScript",
            "nodejs"
          ],
          "author": "Janus Nicon",
          "license": "MIT",
          "bugs": {
            "url": "https://github.com/janusnic/an2-sbs/issues"
          },
          "homepage": "https://github.com/janusnic/an2-sbs#readme"
        }

# npm install
