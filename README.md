# Compare-Arrays-Objects

To compare `Arrays` or `Objects` first stringify them and then compare them.

example:

```js
const a = [1,2,4];
const b = [1,4,2];

JSON.stringify(a) === JSON.stringify(b) =>> false
```

And objects are exactly the same
