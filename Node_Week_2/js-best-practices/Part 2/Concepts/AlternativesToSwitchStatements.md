# Alternatives to Switch Statements

Since Switch Statements usually causes errors in the future, there are many alternatives. 

One alternative are object literals is a comma separated list of name-value pairs which is a great way to minimize the use of global variables. They also work with any data types.

They follow a few syntax rules:

1. Colon separates name from value.
2. Comma separates each name-value pair from the next
3. There is no comma after the last name-value pair.

Below is an example of an object literal:
```
var myObj = {
    numItem: 10,
    myStr: 'insert string here',
    myInv: false
};
```

