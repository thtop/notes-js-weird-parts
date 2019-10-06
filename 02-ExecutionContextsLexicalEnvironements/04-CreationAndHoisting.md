# The Execution Context (Creation and Hoisting)

```js
var a = 'Hello World!';

function b() {
  console.log('Called b!');
}

b(); // Called b!
console.log(a); //Hello World!
```

## Hoisting

```js
b(); // Called b!
console.log(a); // undefined

var a = 'Hello World!';

function b() {
  console.log('Called b!');
}
```

## Error

```js
b(); // Called b!
console.log(a); // ReferenceError: a is not defined

//var a = 'Hello World!';

function b() {
  console.log('Called b!');
}
```

## Execution Context is Created (CREATION PHASE)

- Global Object
- 'this'
- Outer Environment
- Setup Memory Spacee for Variables and Functions **"Hositing"**

```js
b();
console.log(a);

//var a = undefined;
var a = 'Hello World!';

function b() {
  console.log('Called b!');
}
```
