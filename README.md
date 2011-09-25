
memory
======

 	* Node.js module to grab your current memory usage in various formats
 
 	* Why? Pretty common helper function, easier to just require() than /lib/ it
 
```bash
$ npm install memory
```

  	* Example:

```javascript
var memory = require("memory");
var mb = memory(2, true);
console.log("Memory usage: ", mb);
```