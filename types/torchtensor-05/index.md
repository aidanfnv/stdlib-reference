---
layout: stdlib-reference
---

# struct TorchTensor\<T\>

## Description

Represents the handle of a Torch tensor object.


## Generic Parameters

####  <a id="typeparam-T"></a>T

## Methods

* [getView](getview-3.md)
* [dims](dims.md)
* [size](size.md)
* [stride](stride.md)
* [data\_ptr](data_ptr.md)
* [alloc](alloc.md)
* [emptyLike](emptylike-5.md)
* [fillZero](fillzero-4.md)
* [fillValue](fillvalue-4.md)
* [zerosLike](zeroslike-5.md)


```{toctree}
:titlesonly:
:hidden:

alloc <../types/torchtensor-05/alloc>
data_ptr <../types/torchtensor-05/data_ptr>
dims <../types/torchtensor-05/dims>
emptyLike <../types/torchtensor-05/emptylike-5>
fillValue <../types/torchtensor-05/fillvalue-4>
fillZero <../types/torchtensor-05/fillzero-4>
getView <../types/torchtensor-05/getview-3>
size <../types/torchtensor-05/size>
stride <../types/torchtensor-05/stride>
zerosLike <../types/torchtensor-05/zeroslike-5>
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
