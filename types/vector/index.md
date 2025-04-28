---
layout: stdlib-reference
---

# struct vector\<T, N:int\>

*Conforms to:* [IRWArray](../interfaces/irwarray-0123/index.html)\<[T](../interfaces/irwarray-0123/index.html#typeparam-T)\>

*Conditionally conforms to:* [IInteger](../interfaces/iinteger-01/index.html), [IFloat](../interfaces/ifloat-01/index.html), [IDifferentiable](../interfaces/idifferentiable-01/index.html), [ITexelElement](../interfaces/itexelelement-016/index.html)

## Description

An <span class='code'><a href="index.html#decl-N" class="code_var">N</a></span> component vector with elements of type <span class='code'><a href="index.html#typeparam-T" class="code_type">T</a></span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T  = float
####  <a id="decl-N"></a>N  : int = 4

## Fields

####  <a id="decl-elementCount"></a>[elementCount](.html) : int = 2

## Methods

* [getCount](../getcount-3.html)
* [shl](../shl.html)
* [shr](../shr.html)
* [bitAnd](../bitand-3.html)
* [bitOr](../bitor-3.html)
* [bitXor](../bitxor-3.html)
* [bitNot](../bitnot-3.html)
* [and](../and.html)
* [or](../or.html)
* [not](../not.html)
* [toInt](../toint-2.html)
* [toInt64](../toint64-2.html)
* [toUInt](../touint-23.html)
* [toUInt64](../touint64-23.html)
* [lessThan](../lessthan-4.html)
* [lessThanOrEquals](../lessthanorequals-48a.html)
* [equals](../equals.html)
* [add](../add.html)
* [sub](../sub.html)
* [mul](../mul.html)
* [div](../div.html)
* [mod](../mod.html)
* [neg](../neg.html)
* [scale](../scale.html)
* [toFloat](../tofloat-2.html)
* [dzero](../dzero.html)
* [dadd](../dadd.html)
* [dmul](../dmul.html)
* operator$init

## Conditional Conformances

### Conformance to IInteger
`vector<T, N:int>` additionally conforms to `IInteger` when the following conditions are met:

  * [T](index.html#typeparam-T) : [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.html)
### Conformance to IFloat
`vector<T, N:int>` additionally conforms to `IFloat` when the following conditions are met:

  * [T](index.html#typeparam-T) : [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.html)
### Conformance to IDifferentiable
`vector<T, N:int>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T](index.html#typeparam-T) : [IDifferentiable](../interfaces/idifferentiable-01/index.html)
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

Differential <differential-0>
Element <element-0>
add <add>
and <and>
bitAnd <bitand-3>
bitNot <bitnot-3>
bitOr <bitor-3>
bitXor <bitxor-3>
dadd <dadd>
div <div>
dmul <dmul>
dzero <dzero>
elementCount <elementcount-7>
equals <equals>
getCount <getcount-3>
init <init>
lessThan <lessthan-4>
lessThanOrEquals <lessthanorequals-48a>
mod <mod>
mul <mul>
neg <neg>
not <not>
or <or>
scale <scale>
shl <shl>
shr <shr>
sub <sub>
toFloat <tofloat-2>
toInt <toint-2>
toInt64 <toint64-2>
toUInt <touint-23>
toUInt64 <touint64-23>
```
