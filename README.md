<div align="center">
  <a href="http://git.io/rise">
    <img width=13% src="https://cloud.githubusercontent.com/assets/8317250/9425669/c3e1e15e-4953-11e5-92d3-fa86a38278bf.png">
  </a>
</div>
<br>

> Scaffold out a node module with [ES6][es6]+, [Babel][babel], [tape][tape] and [npm scripts][npm-scripts].

[![NPM version][npm-badge]][npm-url]
[![Coveralls Status][coveralls-badge]][coveralls-url]
[![Build Status][travis-badge]][travis-url]
[![Download Status][download-badge]][npm-url]
[![Dependency Status][dep-badge]][dep-url]

# Features

* [Babel][babel]
* [Lint](http://stackoverflow.com/questions/8503559/what-is-linting) with [ESLint](http://eslint.org/)
* [Tests](http://programmers.stackexchange.com/questions/135218/what-is-the-difference-between-writing-test-cases-for-bdd-and-tdd) with [tape][tape] in ES6
* [Travis CI](http://docs.travis-ci.com/user/languages/javascript-with-nodejs/) and [Coveralls](https://coveralls.io) ready
* Productivity   [scripts](https://github.com/bucaran/generator-rise/blob/master/package.json#L13) :horse_racing:
* [Shields.io](http://shields.io/) badges

## Install

```
npm i -g generator-rise
```

## Usage
> You need [Yeoman](http://yeoman.io/) to run this command.

```
yo rise

→ create package.json
→ create README.md
→ create LICENSE
→ create CHANGELOG.md
→ create src/index.js
→ create test/index.js
→ create .editorconfig
→ create .gitignore
→ create .travis.yml
→ create .eslintrc
```

## :beginner: Notes

* Dependencies are automatically installed.

* Add code to `src/index.js` and tests to `test/index.js`.

* Lint, build and test a project with `npm run build`.

* Run only tests with `npm run test`.

* Check coverage with `npm run coverage`.

* Deploy to a remote origin with `npm run deploy`.

* Bump version and publish a package with `npm run major` or `minor/patch`

* Do not forget to enable [Travis](https://travis-ci.org/) and [Coveralls](coveralls.io).


## License

MIT ☭

[npm-url]: https://npmjs.org/package/generator-rise
[npm-badge]: https://img.shields.io/npm/v/generator-rise.svg?style=flat-square

[coveralls-url]: https://coveralls.io/r/bucaran/generator-rise
[coveralls-badge]: https://img.shields.io/coveralls/bucaran/generator-rise.svg?style=flat-square

[travis-url]: https://travis-ci.org/bucaran/generator-rise
[travis-badge]: https://img.shields.io/travis/bucaran/generator-rise.svg?style=flat-square

[dep-url]: https://david-dm.org/bucaran/generator-rise
[dep-badge]: https://david-dm.org/bucaran/generator-rise.svg?style=flat-square

[download-badge]: http://img.shields.io/npm/dm/generator-rise.svg?style=flat-square

[babel]: https://babeljs.io
[tape]: https://github.com/substack/tape
[npm-scripts]: https://docs.npmjs.com/misc/scripts
[es6]: https://github.com/lukehoban/es6features
