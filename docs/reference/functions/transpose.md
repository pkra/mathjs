---
layout: default
---

# Function transpose

Transpose a matrix. All values of the matrix are reflected over its
main diagonal. Only two dimensional matrices are supported.


## Syntax

```js
math.transpose(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Array &#124; Matrix | Matrix to be transposed

### Returns

Type | Description
---- | -----------
Array &#124; Matrix | The transposed matrix


## Examples

```js
var A = [[1, 2, 3], [4, 5, 6]];
math.transpose(A);               // returns [[1, 4], [2, 5], [3, 6]]
```


## See also

[diag](diag.html),
[inv](inv.html),
[subset](subset.html),
[squeeze](squeeze.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->