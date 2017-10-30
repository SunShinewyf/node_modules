## is_sorted
- [项目地址](https://github.com/dcousens/is-sortedn)

### description
check if an Array is sorted


### usage
var sorted = require('is-sorted')

console.log(sorted([1, 2, 3]))
// => true

console.log(sorted([3, 1, 2]))
// => false

// supports custom comparators
console.log(sorted([3, 2, 1], function (a, b) { return b - a })
// => true
