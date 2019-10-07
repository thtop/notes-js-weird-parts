# The Execution Context (Code Execution)

- Global Object
- 'this'
- Outer Environment
- Runs your code

```js
function b() {
  console.log('Called b!');
}

b(); // Called b!

console.log(a); // undefined

var a = 'Hello World';

console.log(a); // Hello World
```
