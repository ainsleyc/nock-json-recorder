# nock-json-recorder

Just a quick hack on the excellent Nock module that allows recorder outputs to be retrieved in JSON format.

```javascript
var nock = require('nock-json-recorder');

nock.recorder.rec(true);
var responses = nock.recorder.playJson();
```
