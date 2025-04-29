---
layout: stdlib-reference
---

# struct matrix\<T, R:int, C:int, L:int\>

*Conforms to:* [IRWArray](../interfaces/irwarray-0123/index)\<[vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), C \>\>

*Conditionally conforms to:* [IFloat](../interfaces/ifloat-01/index), [IDifferentiable](../interfaces/idifferentiable-01/index)

## Description

A matrix with <span class='code'><a href="index#decl-R" class="code_var">R</a></span> rows and <span class='code'><a href="index#decl-C" class="code_var">C</a></span> columns, with elements of type <span class='code'><a href="" class="code_type">T</a></span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T  = float
####  <a id="decl-R"></a>R  : int = 4
####  <a id="decl-C"></a>C  : int = 4
####  <a id="decl-L"></a>L  : int = 0

## Methods

* [getCount](../getcount-3)
* [lessThan](../lessthan-4)
* [lessThanOrEquals](../lessthanorequals-48a)
* [equals](../equals)
* [add](../add)
* [sub](../sub)
* [mul](../mul)
* [div](../div)
* [mod](../mod)
* [neg](../neg)
* [scale](../scale)
* [toFloat](../tofloat-2)
* [dzero](../dzero)
* [dadd](../dadd)
* [dmul](../dmul)
* [init](../init)

## Conditional Conformances

### Conformance to IFloat
`matrix<T, R:int, C:int, L:int>` additionally conforms to `IFloat` when the following conditions are met:

  * [T]() : [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
### Conformance to IDifferentiable
`matrix<T, R:int, C:int, L:int>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T]() : [IDifferentiable](../interfaces/idifferentiable-01/index)

```{toctree}
:titlesonly:
:hidden:

Differential <differential-0>
T <t-0>
add <add>
dadd <dadd>
div <div>
dmul <dmul>
dzero <dzero>
equals <equals>
getCount <getcount-3>
init <init>
lessThan <lessthan-4>
lessThanOrEquals <lessthanorequals-48a>
mod <mod>
mul <mul>
neg <neg>
scale <scale>
sub <sub>
toFloat <tofloat-2>
```
