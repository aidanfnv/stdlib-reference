---
layout: stdlib-reference
---

# struct Array\<T, N:int\>

*Conforms to:* [IRWArray](../../interfaces/irwarray-0123/index.md)\<[T](../../interfaces/irwarray-0123/index.md#typeparam-T)\>

*Conditionally conforms to:* [IDifferentiable](../../interfaces/idifferentiable-01/index.md), [IDifferentiablePtrType](../../interfaces/idifferentiableptrtype-01fi/index.md)

## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="decl-N"></a>N  : int

## Methods

* [getCount](getcount-3.md)
* [dzero](dzero.md)
* [dadd](dadd.md)
* [dmul](dmul.md)

## Conditional Conformances

### Conformance to IDifferentiable
`Array<T, N:int>` additionally conforms to `IDifferentiable` when the following conditions are met:

  * [T](index.md#typeparam-T) : [IDifferentiable](../../interfaces/idifferentiable-01/index.md)
### Conformance to IDifferentiablePtrType
`Array<T, N:int>` additionally conforms to `IDifferentiablePtrType` when the following conditions are met:

  * [T](index.md#typeparam-T) : [IDifferentiablePtrType](../../interfaces/idifferentiableptrtype-01fi/index.md)

```{toctree}
:titlesonly:
:hidden:

Differential <../types/array-0/differential-0>
dadd <../types/array-0/dadd>
dmul <../types/array-0/dmul>
dzero <../types/array-0/dzero>
getCount <../types/array-0/getcount-3>
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
