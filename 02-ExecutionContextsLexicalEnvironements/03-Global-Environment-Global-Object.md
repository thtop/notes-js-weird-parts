# The Global Environment and The Global Object

- Execution context (Global)

  - Global Object (window)
  - 'this'

index.html

```html
<script src="app.js"></script>
```

app.js

```js
// no code
```

console

```js
this[enter];

// window -> Global Object
```

---

- Global
  - Not Inside a Function

app.js

```js
var a = 'Hello World!';

function b() {}
```

console

```js
a; // Hello World!
windows.a; // Hello World!
```
