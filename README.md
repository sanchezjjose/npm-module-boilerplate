[![Build Status](https://travis-ci.org/sanchezjjose/npm-module-boilerplate.svg)](https://travis-ci.org/sanchezjjose/npm-module-boilerplate) [![Coverage Status](https://coveralls.io/repos/sanchezjjose/npm-module-boilerplate/badge.svg?branch=master&service=github)](https://coveralls.io/github/sanchezjjose/npm-module-boilerplate?branch=master)

npm-module-boilerplate
=========

A boilerplate repository for creating npm modules. It supports Travis CI, Istanbul and Coveralls for code coverage, a simple test, and a configured package.json with npm scripts, dependencies, keywords, and more.

## Installation

  `npm install @sanchezjjose/npm-module-boilerplate`

## Usage

At the moment the test code is a number formatter.

    var numFormatter = require('@sanchezjjose/npm-module-boilerplate');

    var formattedNum = numFormatter(35666);
  
  
  Output should be `35,666`


## Tests

  `npm test`

## Contributing

In lieu of a formal style guide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code.
