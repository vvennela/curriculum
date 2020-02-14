produces a SHA-1 hash of the current date combined with the ID from the URL.

Express.js apps can also be mounted to paths that contain a variable by
prepending a `:` to the beginning of a variable name. For instance, in
the following, `app` handles PUT requests in any subdirectory of `/path/`:

```js
app.put('/path/:NAME', function(req, res){ /* ... */ });
```

The given variable is then stored in `req.params`. So, to extract
parameters from within the request handlers, use:

```js
req.params.NAME
```

BONUS

You can use req.param middleware to parse the URL parameter.

For example,

app.param('id', function (req, res, next, id) {
  req.id = id
  ...
  next()
})

app.get('/message/:id', function (req, res, next) {
  console.log(req.id)
  next()
})

Videos: http://bit.ly/1jW1sBf.