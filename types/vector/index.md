---
layout: stdlib-reference
---

# struct vector\<T, N:int\>

*Conforms to:* [IRWArray](../../interfaces/irwarray-0123/index.md)\<[T](../../interfaces/irwarray-0123/index.md#typeparam-T)\>

*Conditionally conforms to:* [IInteger](../../interfaces/iinteger-01/index.md), [IFloat](../../interfaces/ifloat-01/index.md), [IDifferentiable](../../interfaces/idifferentiable-01/index.md), [ITexelElement](../../interfaces/itexelelement-016/index.md)

## Description

An <span class='code'><a href="index.md#decl-N" class="code_var">N</a></span> component vector with elements of type <span class='code'><a href="index.md#typeparam-T" class="code_type">T</a></span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T  = float
####  <a id="decl-N"></a>N  : int = 4

## Fields

####  <a id="decl-elementCount"></a>[elementCount](elementcount-7.md) : int = 2

## Methods

* [getCount](getcount-3.md)
* [shl](shl.md)
* [shr](shr.md)
* [bitAnd](bitand-3.md)
* [bitOr](bitor-3.md)
* [bitXor](bitxor-3.md)
* [bitNot](bitnot-3.md)
* [and](and.md)
* [or](or.md)
* [not](not.md)
* [toInt](toint-2.md)
* [toInt64](toint64-2.md)
* [toUInt](touint-23.md)
* [toUInt64](touint64-23.md)
* [lessThan](lessthan-4.md)
* [lessThanOrEquals](lessthanorequals-48a.md)
* [equals](equals.md)
* [add](add.md)
* [sub](sub.md)
* [mul](mul.md)
* [div](div.md)
* [mod](mod.md)
* [neg](neg.md)
* [scale](scale.md)
* [toFloat](tofloat-2.md)
* [dzero](dzero.md)
* [dadd](dadd.md)
* [dmul](dmul.md)
* operator$init

## Conditional Conformances

### Conformance to IInteger
`vector<T, N:int>` additionally conforms to `IInteger` when the following conditions are met:

  * [T](index.md#typeparam-T) : [\_\_BuiltinIntegerType](../../interfaces/0_builtinintegertype-029g/index.md)
### Conformance to IFloat
`vector<T, N:int>` additionally conforms to `IFloat` when the following conditions are met:

  * [T](index.md#typeparam-T) : [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.md)
### Conformance to IDifferentiable
`vector<T, N:int>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T](index.md#typeparam-T) : [IDifferentiable](../../interfaces/idifferentiable-01/index.md)
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == half
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == float
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == int
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == uint
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == int8\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == int16\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == uint8\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == uint16\_t
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == double
  * [N](index.md#decl-N) == 2
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == uint64\_t
  * [N](index.md#decl-N) == 2
### Conformance to ITexelElement
`vector<T, N:int>` additionally conforms to `ITexelElement` when the following conditions are met:

  * [T](index.md#typeparam-T) == int64\_t
  * [N](index.md#decl-N) == 2

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

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
