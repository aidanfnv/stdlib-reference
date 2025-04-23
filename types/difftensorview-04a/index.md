---
layout: stdlib-reference
---

# struct DiffTensorView\<T, A\>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index.md) = float
####  <a id="typeparam-A"></a>A: [IDiffTensorWrapper](../../interfaces/idifftensorwrapper-015b/index.md) = [AtomicAdd](../atomicadd-06/index.md)

## Fields

####  <a id="decl-diff"></a>[diff](diff.md) : [A](index.md#typeparam-A)
####  <a id="decl-primal"></a>[primal](primal.md) : [TensorView](../tensorview-06/index.md)\<[T](../tensorview-06/index.md#typeparam-T)\>

## Methods

* [size](size.md)
* [dims](dims.md)
* [stride](stride.md)
* [init](init.md)
* [load](load.md)
* [store](store.md)
* [subscript](subscript.md)
* [loadOnce](loadonce-4.md)
* [storeOnce](storeonce-5.md)


```{toctree}
:titlesonly:
:hidden:

diff <../types/difftensorview-04a/diff>
dims <../types/difftensorview-04a/dims>
init <../types/difftensorview-04a/init>
load <../types/difftensorview-04a/load>
loadOnce <../types/difftensorview-04a/loadonce-4>
primal <../types/difftensorview-04a/primal>
size <../types/difftensorview-04a/size>
store <../types/difftensorview-04a/store>
storeOnce <../types/difftensorview-04a/storeonce-5>
stride <../types/difftensorview-04a/stride>
subscript <../types/difftensorview-04a/subscript>
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
