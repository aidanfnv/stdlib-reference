---
layout: stdlib-reference
---

# struct vector\<T, N:int\>

*Conforms to:* [IRWArray](../../interfaces/irwarray-0123/index.html)\<[T](../../interfaces/irwarray-0123/index.html#typeparam-T)\>

*Conditionally conforms to:* [IInteger](../../interfaces/iinteger-01/index.html), [IFloat](../../interfaces/ifloat-01/index.html), [IDifferentiable](../../interfaces/idifferentiable-01/index.html), [ITexelElement](../../interfaces/itexelelement-016/index.html)

## Description

An <span class='code'><a href="index.html#decl-N" class="code_var">N</a></span> component vector with elements of type <span class='code'><a href="index.html#typeparam-T" class="code_type">T</a></span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T  = float
####  <a id="decl-N"></a>N  : int = 4

## Fields

####  <a id="decl-elementCount"></a>[elementCount](elementcount-7.html) : int = 2

## Methods

* [getCount](getcount-3.html)
* [shl](shl.html)
* [shr](shr.html)
* [bitAnd](bitand-3.html)
* [bitOr](bitor-3.html)
* [bitXor](bitxor-3.html)
* [bitNot](bitnot-3.html)
* [and](and.html)
* [or](or.html)
* [not](not.html)
* [toInt](toint-2.html)
* [toInt64](toint64-2.html)
* [toUInt](touint-23.html)
* [toUInt64](touint64-23.html)
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
* operator$init

## Conditional Conformances

### Conformance to IInteger
`vector<T, N:int>` additionally conforms to `IInteger` when the following conditions are met:

  * [T](index.html#typeparam-T) : [\_\_BuiltinIntegerType](../../interfaces/0_builtinintegertype-029g/index.html)
### Conformance to IFloat
`vector<T, N:int>` additionally conforms to `IFloat` when the following conditions are met:

  * [T](index.html#typeparam-T) : [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.html)
### Conformance to IDifferentiable
`vector<T, N:int>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T](index.html#typeparam-T) : [IDifferentiable](../../interfaces/idifferentiable-01/index.html)
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == half
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == float
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == int
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == uint
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == int8\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == int16\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == uint8\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == uint16\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == double
  * [N](index.html#decl-N) == 2
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == uint64\_t
  * [N](index.html#decl-N) == 2
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.html#typeparam-T) == int64\_t
  * [N](index.html#decl-N) == 2

```{toctree}
:titlesonly:
:hidden:

Differential <../types/vector/differential-0>
Element <../types/vector/element-0>
add <../types/vector/add>
and <../types/vector/and>
bitAnd <../types/vector/bitand-3>
bitNot <../types/vector/bitnot-3>
bitOr <../types/vector/bitor-3>
bitXor <../types/vector/bitxor-3>
dadd <../types/vector/dadd>
div <../types/vector/div>
dmul <../types/vector/dmul>
dzero <../types/vector/dzero>
elementCount <../types/vector/elementcount-7>
equals <../types/vector/equals>
getCount <../types/vector/getcount-3>
init <../types/vector/init>
lessThan <../types/vector/lessthan-4>
lessThanOrEquals <../types/vector/lessthanorequals-48a>
mod <../types/vector/mod>
mul <../types/vector/mul>
neg <../types/vector/neg>
not <../types/vector/not>
or <../types/vector/or>
scale <../types/vector/scale>
shl <../types/vector/shl>
shr <../types/vector/shr>
sub <../types/vector/sub>
toFloat <../types/vector/tofloat-2>
toInt <../types/vector/toint-2>
toInt64 <../types/vector/toint64-2>
toUInt <../types/vector/touint-23>
toUInt64 <../types/vector/touint64-23>
```
