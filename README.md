
> Check if something is a positive number


## Install

```
$ npm install --save memen-isPositive
```


## Usage

```js
const memenisPositive = require('memen-isPositive');

isPositive(1);
//=> true

isPositive(0);
//=> false

isPositive(-1);
//=> false

isPositive('1');
//=> false

isPositive(Number(1))
//=> true
```
