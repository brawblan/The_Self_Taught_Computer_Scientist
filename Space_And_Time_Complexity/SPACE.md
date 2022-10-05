# SPACE COMPLEXITY

## space complexity
- the amount of memory space your algorithm needs <br />
- includes fixed space, data structure, and temporary space

## fixed space
- the amount of memory an algorithm requires

## data structure
- the amount of memory a program requires to store the data set

## temporary space
- the amount of memory an algorithm needs for intermediary processing
<hr>

## constant space complexity
<p>This would be considered O(1), or constant time, because the algorithm does not require more space as <em>n</em> gets larger.</p>

```js
let x = 1
const n = 5
for (let i = 0; i < n; i++) {
  x *= i
}
```

## linear space complexity
<p>The algorithm below has a Big O of O(<em>n</em>) beacuse the amount of space grows as <em>n</em> grows.</p>

```js
let x = 1
const n = 5
let arr = []
for (let i = 0; i < n; i++) {
  arr.push(x)
  x *= i
}
```
