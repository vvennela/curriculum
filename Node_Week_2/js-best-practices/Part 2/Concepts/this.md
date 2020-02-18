# ``this`` keyword

``this`` points to an object that it belongs to. The placement of ``this`` will determine where it belongs.

Consider the following example:

``` javascript
var teacher = {
  firstName: "John",
  lastName : "Smith",
  id       : 1234,
  subject  : math,
  class : function() {
    return this.subject + " taught by " + this.firstName + " " + this.lastName;
  }
};
```
The function above will return "math taught by John Smith".

If ``this`` is alone, is it considered to be placed in Global object.
For example:
```javascript
var x = this;
```

If ``this`` is in a method, it points to the owner of the Method.
For example, from the example above,
```javascript
  class : function() {
    return this.subject + " taught by " + this.firstName + " " + this.lastName;
  }
```
``this`` refers to the teacher object.

If ``this`` is in a function, the owner will be automatically set to the default.
For example:
``` javascript
NewFuntion function(){
  return this;
}
```


