Remeber that we are creating an Express.js app that outputs "Hello World!" when somebody goes to `/home`.

So instead of responding with
a string on `'/'`, we want it to respond with a string on `'/home'`.

The port number should be `process.argv[2]` instead of `3000`.

```js
app.listen(process.argv[2])
```

Videos: http://bit.ly/1jW1sBf.