## arr-dedupe
- [项目地址](https://github.com/seriousManual/dedupe)

### description
removes duplicates from your array.


### usage
- simple type
```js
var dedupe = require('dedupe')

var a = [1, 2, 2, 3]
var b = dedupe(a)
console.log(b)

//result: [1, 2, 3]
```

- complex type
```js
var dedupe = require('dedupe')

var aa = [{a: 2}, {a: 1}, {a: 1}, {a: 1}]
var bb = dedupe(aa)
console.log(bb)

//result: [{a: 2}, {a: 1}]
```