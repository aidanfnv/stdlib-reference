---
layout: stdlib-reference
---

# struct AtomicAdd

*Conforms to:* [IDiffTensorWrapper](../../interfaces/idifftensorwrapper-015b/index.md)

## Fields

####  <a id="decl-diff"></a>[diff](diff.md) : [TensorView](../tensorview-06/index.md)\<float\>

## Methods

* init
* [load\_forward](load_forward.md)
* [load\_backward](load_backward.md)
* [store\_forward](store_forward.md)
* [store\_backward](store_backward.md)
* [loadOnce\_forward](loadonce_forward-4.md)
* [loadOnce\_backward](loadonce_backward-4.md)
* [storeOnce\_forward](storeonce_forward-5.md)
* [storeOnce\_backward](storeonce_backward-5.md)


```{toctree}
:titlesonly:
:hidden:

diff <../types/atomicadd-06/diff>
loadOnce_backward <../types/atomicadd-06/loadonce_backward-4>
loadOnce_forward <../types/atomicadd-06/loadonce_forward-4>
load_backward <../types/atomicadd-06/load_backward>
load_forward <../types/atomicadd-06/load_forward>
storeOnce_backward <../types/atomicadd-06/storeonce_backward-5>
storeOnce_forward <../types/atomicadd-06/storeonce_forward-5>
store_backward <../types/atomicadd-06/store_backward>
store_forward <../types/atomicadd-06/store_forward>
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
