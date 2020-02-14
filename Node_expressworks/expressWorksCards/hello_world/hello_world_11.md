This is how we can create an Express.js app on port 3000, that responds with
a string on `'/'`:

```js
const express = require('express')
const app = express()
app.get('/', function(req, res) {
  res.end('Hello World!')
})
app.listen(3000)
```
