# node-ypp

YOLK's Pretty Print for Node

## Abstract

Returns `JSON.stringify(object, null, 2);`

I use this everywhere.

## Installation

```sh
npm i --save ypp
```

## Usage

```javascript
var pp = require('ypp');
var a = {a:1,b:2,c:'apple'};
console.log(pp(a));
// {
//   "a": 1,
//   "b": 2,
//   "c": "apple"
// }
```

```javascript
import pp from 'ypp';
const a = {a:1, b:2, c:'three'};
console.log(pp(a));
// {
//   "a": 1,
//   "b": 2,
//   "c": "three"
// }
```
