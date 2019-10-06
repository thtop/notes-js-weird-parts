# Conceptual Aside (Javascript and 'undefined')

## JavaScript and 'undefined'

- special keyword or special value
- value -> never set the value

```js
var a;

console.log(a); // undefined
```

```js
//var a;

console.log(a); //ReferenceError: a is not defined
```

```js
var a;
console.log(a);

if (a === undefined) {
  console.log('a is undefined!'); // a is undefined!
} else {
  console.log('a is defined!');
}
```

```js
var a = 'Hello world';
console.log(a); // Hello world

if (a === undefined) {
  console.log('a is undefined!');
} else {
  console.log('a is defined!'); // a is defined!
}
```

```js
console.log(a); // Error: ReferenceError: a is not defined

if (a === undefined) {
  console.log('a is undefined!');
} else {
  console.log('a is defined!'); // a is defined!
}
```

## Never do this!

```js
var a = 'Hello World!';
console.log(a);

a = undefined; // never set the value

if (a === undefined) {
  console.log('a is undefined!'); // a is undefined!
} else {
  console.log('a is defined!');
}
```
