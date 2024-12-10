# Type Error in TypeScript
This repository demonstrates a common type error in TypeScript. The function `add` expects two numbers as parameters, but the second parameter in the call to `add` is a string. This will result in a type error.

## Bug
The bug is in the following line of code:
```typescript
let result = add(1, "2");
```
This will result in a type error because the function `add` expects two numbers as parameters, but the second parameter is a string.

## Solution
The solution is to make sure that the second parameter is a number. This can be done in several ways, for example:

```typescript
let result = add(1, 2);
```

```typescript
let result = add(1, parseInt("2"));
```
