# Conceptual Aside (Name-Value Pairs and Objects)

## Name-Value Pairs

> A name which maps to a unique value

- The name may be defined more than once, but only can have one value in any given context.
- That value may be more name/value pairs.

```js
Address = '100 Main St.';
```

## Objects

> A collection of name value pairs

- The simplest definition when talking about **JavaScript**.

```js
/*
name
  name
    name/value
    name/value
    name/value
  name
    name/value
    name/value
    name/value
*/

Address: {
    Street: 'Main',
    Number: 100,
    Apartment: {
        Floor: 3,
        Number: 301
    }
}
```
