# offline-to-online
offline to online on nodejs and browser

## install
```
npm install offline-to-online
```

## api
### offline to online on browser
```javascript
'use strict';

var q = require('qiao-is-online-browser');

// callback
// time, interval time, default is 3*1000ms
q.offlineToOnline(function(){
    console.log('offline-to-online');
}, 3 * 1000);
```

## version
### 0.0.1.20200821
1. init project
2. on browser ok
3. string offline online
4. fix