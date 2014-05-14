# demo-gh-pages-publish

[![Build Status](https://secure.travis-ci.org/bartvds/demo-gh-pages-publish.png?branch=master)](http://travis-ci.org/bartvds/demo-gh-pages-publish)

> Use grunt and Travis-CI to publish content to your github-pages

This guide uses the described flow to publish to [bartvds.github.io/demo-gh-pages-publish](http://bartvds.github
.io/demo-gh-pages-publish)


:warning: work-in-progress


https://github.com/settings/applications

http://docs.travis-ci.com/user/build-configuration/#Secure-environment-variables

http://docs.travis-ci.com/user/encryption-keys/

https://github.com/tschaub/grunt-gh-pages#optionssilent

## Build

Have grunt

````bash
$ npm install grunt-cli -g
````

Install dependencies

````bash
$ npm install
````

Rebuild site in `./public/`

````bash
$ grunt build
````

Clean `./public/`

````bash
$ grunt build
````


## Contributing

Contributions are very welcome. In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).