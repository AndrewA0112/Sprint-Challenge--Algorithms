#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) `O(n)` The function only runs as many times as `n` the `n * n * n` and `n * n` cancel each other and leave it as `n`


b) `O(n)` The function just loops through `n`, nothing extra


c) `O(n)` The function operates over bunnyEars `n` + 1 times.


## Exercise II

- Start at floor that is equal to n//2
- If egg breaks go down halfway, else go up halfway (Go up/down **(n//2{Latest n//2})//2** )
- Example: n = 100
- Start at floor 50(n//2)
- Drop Egg, if breaks go down to 25((n//2)//2), else go up 25((n//2)//2)
- Repeat until the floor above breaks egg but the floor you are on doesn't break the egg


