## arr-flatten
- [项目地址](https://github.com/jonschlinkert/arr-diff)

### description
Returns an array with only the unique values from the first array, by excluding all values from additional arrays using strict equality for comparisons.

### usage
var arr-diff = require('arr-diff');
arr-diff(['a', 'b', 'c'], ['b', 'c', 'e']))  //['a']
arr-diff(['x', 'b', 'c', 'e', 'y'], ['b', 'x', 'e'])) //['c', 'y']

### key source code
```js
  while (++idx < len) {
    arr = diffArray(arr, arguments[idx]);
  }
  return arr;

  //diffArray 返回每次第一个数组还剩的unique的数组元素
```
