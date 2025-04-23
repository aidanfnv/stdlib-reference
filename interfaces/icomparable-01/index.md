---
layout: stdlib-reference
---

# interface IComparable

## Description

Represents types that can be compared.
Implemented by all builtin integer and floating point scalar or vector types.


## Methods

* [equals](equals.md)
* [lessThan](lessthan-4.md)
* [lessThanOrEquals](lessthanorequals-48a.md)


```{toctree}
:titlesonly:
:hidden:

equals <../interfaces/icomparable-01/equals>
lessThan <../interfaces/icomparable-01/lessthan-4>
lessThanOrEquals <../interfaces/icomparable-01/lessthanorequals-48a>
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
