---
layout: stdlib-reference
---

# struct matrix\<T, R:int, C:int, L:int\>

*Conforms to:* [IRWArray](../../interfaces/irwarray-0123/index.md)\<[vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), C \>\>

*Conditionally conforms to:* [IFloat](../../interfaces/ifloat-01/index.md), [IDifferentiable](../../interfaces/idifferentiable-01/index.md)

## Description

A matrix with <span class='code'><a href="index.md#decl-R" class="code_var">R</a></span> rows and <span class='code'><a href="index.md#decl-C" class="code_var">C</a></span> columns, with elements of type <span class='code'><a href="t-0.md" class="code_type">T</a></span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T  = float
####  <a id="decl-R"></a>R  : int = 4
####  <a id="decl-C"></a>C  : int = 4
####  <a id="decl-L"></a>L  : int = 0

## Methods

* [getCount](getcount-3.md)
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
* [init](init.md)

## Conditional Conformances

### Conformance to IFloat
`matrix<T, R:int, C:int, L:int>` additionally conforms to `IFloat` when the following conditions are met:

  * [T](t-0.md) : [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.md)
### Conformance to IDifferentiable
`matrix<T, R:int, C:int, L:int>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T](t-0.md) : [IDifferentiable](../../interfaces/idifferentiable-01/index.md)

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

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
