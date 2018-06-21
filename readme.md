# Atomizer.js

**Compile one utility per line**

```javascript
/*
    v=x.x.x keys=fn1,fn2,fn5 node compile
*/
var $$ = typeof(global) === 'object' ? global : window;
$$.fn1(a,b) = function(){};$$.fn1.prototype={}; // (function|string|number|object|date)
$$.fn2(a,b) = function(){};
$$.fn5(a,b) = function(){};
```

- Allows partial builds
- Generates recompilation command
- Checks version mismatch
- Checks key <-> implementation mismatch
- Supports function prototyping
- Supports browser and node enviroment
