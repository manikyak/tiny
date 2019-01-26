# @Manikyak/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@Manikyak/tiny.svg)](https://www.npmjs.com/package/@manikyak/tiny)


Removes all spaces from a string.

## Install

```
$ npm install @manikyak/tiny 
```

## Usage

```js
const tiny = require("@manikyak/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
