# TypeScript ESLint Demo

This is a demo project using for TypeScript and ESLint.


## The goal

Detect issues in code and auto fix them using command.

For example:

```ts
console.log("Hello world" )

const a = 1

if(a + 1 == 2) {
  console.log('Hello');
}
```

should be changed to:

```ts
console.log('Hello world');

const a = 1;

if (a + 1 === 2) {
  console.log('Hello');
}

```


## References

- https://typescript-eslint.io/docs/linting/
