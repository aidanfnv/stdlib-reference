---
layout: stdlib-reference
---

# struct matrix\<T, R:int, C:int, L:int\>

*Conforms to:* [IRWArray](../../interfaces/irwarray-0123/index.html)\<[vector](../vector/index.html)\<[T](../vector/index.html#typeparam-T), C \>\>

*Conditionally conforms to:* [IFloat](../../interfaces/ifloat-01/index.html), [IDifferentiable](../../interfaces/idifferentiable-01/index.html)

## Description

A matrix with <span class='code'><a href="index.html#decl-R" class="code_var">R</a></span> rows and <span class='code'><a href="index.html#decl-C" class="code_var">C</a></span> columns, with elements of type <span class='code'><a href="t-0.html" class="code_type">T</a></span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T  = float
####  <a id="decl-R"></a>R  : int = 4
####  <a id="decl-C"></a>C  : int = 4
####  <a id="decl-L"></a>L  : int = 0

## Methods

* [getCount](getcount-3.html)
* [lessThan](lessthan-4.html)
* [lessThanOrEquals](lessthanorequals-48a.html)
* [equals](equals.html)
* [add](add.html)
* [sub](sub.html)
* [mul](mul.html)
* [div](div.html)
* [mod](mod.html)
* [neg](neg.html)
* [scale](scale.html)
* [toFloat](tofloat-2.html)
* [dzero](dzero.html)
* [dadd](dadd.html)
* [dmul](dmul.html)
* [init](init.html)

## Conditional Conformances

### Conformance to IFloat
`matrix<T, R:int, C:int, L:int>` additionally conforms to `IFloat` when the following conditions are met:

  * [T](t-0.html) : [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.html)
### Conformance to IDifferentiable
`matrix<T, R:int, C:int, L:int>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T](t-0.html) : [IDifferentiable](../../interfaces/idifferentiable-01/index.html)

```{toctree}
:titlesonly:
:hidden:

Differential <../types/matrix/differential-0>
T <../types/matrix/t-0>
add <../types/matrix/add>
dadd <../types/matrix/dadd>
div <../types/matrix/div>
dmul <../types/matrix/dmul>
dzero <../types/matrix/dzero>
equals <../types/matrix/equals>
getCount <../types/matrix/getcount-3>
init <../types/matrix/init>
lessThan <../types/matrix/lessthan-4>
lessThanOrEquals <../types/matrix/lessthanorequals-48a>
mod <../types/matrix/mod>
mul <../types/matrix/mul>
neg <../types/matrix/neg>
scale <../types/matrix/scale>
sub <../types/matrix/sub>
toFloat <../types/matrix/tofloat-2>
```
