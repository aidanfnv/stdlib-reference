---
layout: stdlib-reference
---

# struct TensorView\<T\>

## Description

Represents a GPU view of a tensor.


## Generic Parameters

####  <a id="typeparam-T"></a>T

## Methods

* [data\_ptr](data_ptr.md)
* [data\_ptr\_at](data_ptr_at.md)
* [init](init.md)
* [load](load.md)
* [store](store.md)
* [InterlockedAdd](interlockedadd-0b.md)
* [dims](dims.md)
* [size](size.md)
* [stride](stride.md)
* [subscript](subscript.md)
* [InterlockedMin](interlockedmin-0b.md)
* [InterlockedMax](interlockedmax-0b.md)
* [InterlockedAnd](interlockedand-0b.md)
* [InterlockedOr](interlockedor-0b.md)
* [InterlockedXor](interlockedxor-0b.md)
* [InterlockedExchange](interlockedexchange-0b.md)
* [InterlockedCompareExchange](interlockedcompareexchange-0bi.md)


```{toctree}
:titlesonly:
:hidden:

InterlockedAdd <../types/tensorview-06/interlockedadd-0b>
InterlockedAnd <../types/tensorview-06/interlockedand-0b>
InterlockedCompareExchange <../types/tensorview-06/interlockedcompareexchange-0bi>
InterlockedExchange <../types/tensorview-06/interlockedexchange-0b>
InterlockedMax <../types/tensorview-06/interlockedmax-0b>
InterlockedMin <../types/tensorview-06/interlockedmin-0b>
InterlockedOr <../types/tensorview-06/interlockedor-0b>
InterlockedXor <../types/tensorview-06/interlockedxor-0b>
data_ptr <../types/tensorview-06/data_ptr>
data_ptr_at <../types/tensorview-06/data_ptr_at>
dims <../types/tensorview-06/dims>
init <../types/tensorview-06/init>
load <../types/tensorview-06/load>
size <../types/tensorview-06/size>
store <../types/tensorview-06/store>
stride <../types/tensorview-06/stride>
subscript <../types/tensorview-06/subscript>
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
