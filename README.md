# math-logn

Calculates the n-base logarithm of a number.  

JavaScript provides methods to calculate the natural, base-2 and base-10 logarithm, i.e., `Math.log()`, `Math.log2()` and `Math.log10()` respectively.   
... and that's it! With this method you can calculate an `n`-base logarithm.

> `Math.logn(x,n)` - $\log_n x$

```
const four = Math.logn(81,3);
// the base-3 logarithm of 81

console.log(four);
// 4
```
