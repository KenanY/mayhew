# mayhew

[![Build Status][travis-svg]][travis]
[![Dependency Status][gemnasium-svg]][gemnasium]

[Mayhew's formula][1] for calculating one-repetition maximum.

## Example

``` javascript
var mayhew = require('mayhew');

mayhew(100, 10);
// => 130
```

## Installation

``` bash
$ npm install mayhew
```

## API

``` javascript
var mayhew = require('mayhew');
```

### `mayhew(weight, reps)`

Given _Number_ `weight` and _Number_ `reps`, returns Mayhew's one-repetition
maximum as a _Number_.


   [travis]: https://travis-ci.org/KenanY/mayhew
   [travis-svg]: https://img.shields.io/travis/KenanY/mayhew.svg
   [gemnasium]: https://gemnasium.com/KenanY/mayhew
   [gemnasium-svg]: https://img.shields.io/gemnasium/KenanY/mayhew.svg
