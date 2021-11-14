<!-- Note: This file is automatically generated from source code comments. Changes made in this file will be overridden. -->

# Function log2

Calculate the 2-base of a value. This is the same as calculating `log(x, 2)`.

For matrices, the function is evaluated element wise.


## Syntax

```js
math.log2(x)
```

### Parameters

Parameter | Type | Description
--------- | ---- | -----------
`x` | number &#124; BigNumber &#124; Complex &#124; Array &#124; Matrix |  Value for which to calculate the logarithm.

### Returns

Type | Description
---- | -----------
number &#124; BigNumber &#124; Complex &#124; Array &#124; Matrix |  Returns the 2-base logarithm of `x`


## Examples

```js
math.log2(0.03125)           // returns -5
math.log2(16)                // returns 4
math.log2(16) / math.log2(2) // returns 4
math.pow(2, 4)               // returns 16
```


## See also

[exp](exp.md),
[log](log.md),
[log1p](log1p.md),
[log10](log10.md)