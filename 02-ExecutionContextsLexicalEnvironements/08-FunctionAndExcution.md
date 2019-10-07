# Function Invocation and the Execution Stack

## Invocation

> Running a function

- In JavaScript, by using parenthesis()

```js
function b() {}

function a() {
  b();
}

a();
```

```js
function a() {
  b();
  var c;
}

function b() {
  var d;
}
a();
var d;
```
