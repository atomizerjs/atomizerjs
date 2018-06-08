# Atomizer.js

**Compile utilities to single object, one utility per line**

```javascript
// keys=fn1,fn2,fn5 node compile
var U = {};
U.fn1(a,b) = function(){};U.fn1.prototype={}; // (function|string|number|object|date)
U.fn2(a,b) = function(){};
U.fn5(a,b) = function(){};
```

- Supports partial build with version checking and check if function is implemented or not
- Supports **function prototyping**
- Plays well with both **browser** and **node** enviroment
- :eyeglasses: Build is well readable API reference
