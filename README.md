

## Getting Started

This library is distributed in both the npm and bower packaging systems.

```sh
npm install reitscore-mnemonic
bower install reitscore-mnemonic
```


```javascript
var Mnemonic = require('reitscore-mnemonic');
var code = new Mnemonic(Mnemonic.Words.SPANISH);
code.toString(); 
var xpriv = code.toHDPrivateKey();
```



