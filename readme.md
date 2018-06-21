# Atomizer.js

**Compile one utility per line**

```javascript
/*
    v=x.x.x keys=fn1,fn2,fn5 node compile
*/
var $$ = typeof(global) === 'object' ? global : window;
$$.fn1 = function(a,b){};$$.fn1.prototype={}; // (function|string|number|object|date)
$$.fn2 = function(a,b){};
$$.fn5 = function(a,b){};
```

- Allows partial builds
- Generates recompilation command
- Checks version mismatch
- Checks key <-> implementation mismatch
- Supports function prototyping
- Supports browser and node enviroment
