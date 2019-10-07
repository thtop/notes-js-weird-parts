# Functions, Context, and Variable Environments

## Variable Environments

> Where the variables live

- And how they relate to each other in memory

```js
function b() {
  var myVar; // undefined
}

function a() {
  var myVar = 2;
  b();
}

var myVar = 1;
a(); // 2
```
