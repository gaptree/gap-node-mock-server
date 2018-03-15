# gap-node-mock-server

## install

#### a. yarn add gap-node-mock-server --save-dev
#### b. add script to package.json
``` javascript
"scripts": {
    "mock": "pm2 start app.js --watch",
    "stopMock": "pm2 stop app.js"
  }
```
## require
  #### a.create bin/gap-front-mock.js
  #### b.write script
  
 ``` javascript
#!/usr/bin/env node

const path = require('path');
const fs = require('fs');

require('gap-node-mock-server')({
  baseDir: ;
  port:  ;
})
```
