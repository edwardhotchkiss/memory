
memory
======

 	* Node.js module to grab your current memory usage in various formats
 	* Why? Pretty common helper function, easier to just require() than /lib/ it

 	* @params
 	* kDec : @Integer (nearest decimel rounding)
 	* returnMBString : @Boolean (return as a float or as a string appended with "MB")
 
```bash
$ npm install memory
```

  	* Example:

```javascript
var memory = require("memory");
var mb = memory(2, true);
console.log("Memory usage: ", mb);
```