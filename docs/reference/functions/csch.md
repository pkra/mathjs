---
layout: default
---

# Function csch

Calculate the hyperbolic cosecant of a value,
defined as `csch(x) = 1 / sinh(x)`.

For matrices, the function is evaluated element wise.


## Syntax

```js
math.csch(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | Number &#124; Boolean &#124; Complex &#124; Unit &#124; Array &#124; Matrix | Function input

### Returns

Type | Description
---- | -----------
Number &#124; Complex &#124; Array &#124; Matrix | Hyperbolic cosecant of x


## Examples

```js
// csch(x) = 1/ sinh(x)
math.csch(0.5);       // returns 1.9190347513349437
1 / math.sinh(0.5);   // returns 1.9190347513349437
```


## See also

[sinh](sinh.html),
[sech](sech.html),
[coth](coth.html)


<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->