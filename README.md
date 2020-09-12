# Remove Duplicates

**Remove duplicate values from a array**

_All codes in app.js file_

## Code Snippet

```javascript
let arr = [1, 2, 2, 3, 4, 4, 5];

// removing duplication
let uniqueArr = [...new Set(arr)];
console.log(uniqueArr);
```

### Simple I/O

- **_Before_**

```diff
[1, 2, 2, 3, 4, 4, 5]
```

- **_Output_**

```diff
 [ 1, 2, 3, 4, 5 ]
```
