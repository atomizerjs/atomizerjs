# Atomizer.js

**Compile utilities to single object, one utility per line**

```javascript
// keys=fn1,fn2,fn5 node compile
var U = {};
U.fn1(a,b) = function(){};U.fn1.prototype={}; // (function|string|number|object|date)
U.fn2(a,b) = function(){};
U.fn5(a,b) = function(){};
```

- Allows **partial builds**
- :arrows_clockwise: Auto-generates **recompilation command** at 1st line
- Checks **version mismatch**
- Checks **key :left_right_arrow: implementation mismatch**
- Supports **function prototyping**
- Plays well with both **browser** and **node** enviroments
- :eyeglasses: Build is well **readable API** reference

[Example of usage](https://github.com/tomassentkeresty/utilizerjs/blob/h/compile.js)
