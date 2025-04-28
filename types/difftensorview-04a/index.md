---
layout: stdlib-reference
---

# struct DiffTensorView\<T, A\>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.html) = float
####  <a id="typeparam-A"></a>A: [IDiffTensorWrapper](../interfaces/idifftensorwrapper-015b/index.html) = [AtomicAdd](../types/atomicadd-06/index.html)

## Fields

####  <a id="decl-diff"></a>[diff](.html) : [A](index.html#typeparam-A)
####  <a id="decl-primal"></a>[primal](.html) : [TensorView](../types/tensorview-06/index.html)\<[T](../types/tensorview-06/index.html#typeparam-T)\>

## Methods

* [size](../size.html)
* [dims](../dims.html)
* [stride](../stride.html)
* [init](../init.html)
* [load](../load.html)
* [store](../store.html)
* [subscript](../subscript.html)
* [loadOnce](../loadonce-4.html)
* [storeOnce](../storeonce-5.html)


```{toctree}
:titlesonly:
:hidden:

diff <diff>
dims <dims>
init <init>
load <load>
loadOnce <loadonce-4>
primal <primal>
size <size>
store <store>
storeOnce <storeonce-5>
stride <stride>
subscript <subscript>
```
