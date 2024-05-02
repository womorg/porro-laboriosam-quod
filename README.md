# @womorg/porro-laboriosam-quod <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Map` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @womorg/porro-laboriosam-quod
```

## Usage/Examples

```js
var map = new Map();
var obj = {};

map.set(1, 2).set(obj, 4);

map.get(obj); // 4
map.has(3); // false
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@womorg/porro-laboriosam-quod
[npm-version-svg]: https://versionbadg.es/es-shims/@womorg/porro-laboriosam-quod.svg
[deps-svg]: https://david-dm.org/es-shims/@womorg/porro-laboriosam-quod.svg
[deps-url]: https://david-dm.org/es-shims/@womorg/porro-laboriosam-quod
[dev-deps-svg]: https://david-dm.org/es-shims/@womorg/porro-laboriosam-quod/dev-status.svg
[dev-deps-url]: https://david-dm.org/es-shims/@womorg/porro-laboriosam-quod#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@womorg/porro-laboriosam-quod.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@womorg/porro-laboriosam-quod.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@womorg/porro-laboriosam-quod.svg
[downloads-url]: https://npm-stat.com/charts.html?package=es-shims/@womorg/porro-laboriosam-quod
[codecov-image]: https://codecov.io/gh/es-shims/@womorg/porro-laboriosam-quod/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/es-shims/@womorg/porro-laboriosam-quod/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/es-shims/@womorg/porro-laboriosam-quod
[actions-url]: https://github.com/womorg/porro-laboriosam-quod/actions
