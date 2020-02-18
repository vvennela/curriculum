# ``===`` vs ``==``

Both of these operators compare two values for equality, but what is the difference between the two?

``===``, is the triple equals operator that is known as the *strict comparison* operator because
it will only return true if the values are equal value and equal types.

``==``, is the double equals operator that is known as the *abstract comparison* operator because
it converts the variables to have the same type before comparing. It will then return true
if they are the same.

For example:
``` javascript
var test_one = 5;
var test_two = 5;
var test_string = "5";  // this type is a string

console.log(test_one == test_two);  // returns true
console.log(test_one === test_two);  // returns true
console.log(test_one == test_string); // returns true
console.log(test_one === test_string); // returns false
```

Since test_one is a number and test_string is a string, 
using the twiple equals operator will return false.
