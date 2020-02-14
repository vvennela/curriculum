(211.md)

A middleware is added by calling `use()` on the application and passing the
middleware as a parameter.

To parse `x-www-form-urlencoded` request bodies, Express.js can use `urlencoded()`
middleware from the `body-parser` module.



```js
const bodyparser = require('body-parser')
app.use(bodyparser.urlencoded({extended: false}))
```

