# gap-node-mock-server

## install

#### a. yarn add gap-node-mock-server --save-dev
#### b. add script to package.json
``` javascript
"scripts": {
    "mock": "./node_modules/pm2/bin/pm2 start app.js --watch",
    "stopMock": "./node_modules/pm2/bin/pm2 sop app.js"
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
