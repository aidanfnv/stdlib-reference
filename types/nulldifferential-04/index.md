---
layout: stdlib-reference
---

# struct NullDifferential

*Conforms to:* [IDifferentiable](../../interfaces/idifferentiable-01/index.md)

## Fields

####  <a id="decl-dummy"></a>[dummy](dummy.md) : uint

## Methods

* init
* [dzero](dzero.md)
* [dadd](dadd.md)
* [dmul](dmul.md)


```{toctree}
:titlesonly:
:hidden:

Differential <../types/nulldifferential-04/differential-0>
dadd <../types/nulldifferential-04/dadd>
dmul <../types/nulldifferential-04/dmul>
dummy <../types/nulldifferential-04/dummy>
dzero <../types/nulldifferential-04/dzero>
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
