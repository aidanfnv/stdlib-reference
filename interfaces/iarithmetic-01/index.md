---
layout: stdlib-reference
---

# interface IArithmetic

*Inherits from:* [IComparable](../icomparable-01/index.md)

## Description

Represents types that provide arithmetic operations.


## Methods

* [add](add.md)
* [sub](sub.md)
* [mul](mul.md)
* [div](div.md)
* [mod](mod.md)
* [neg](neg.md)
* [init](init.md)


```{toctree}
:titlesonly:
:hidden:

add <../interfaces/iarithmetic-01/add>
div <../interfaces/iarithmetic-01/div>
init <../interfaces/iarithmetic-01/init>
mod <../interfaces/iarithmetic-01/mod>
mul <../interfaces/iarithmetic-01/mul>
neg <../interfaces/iarithmetic-01/neg>
sub <../interfaces/iarithmetic-01/sub>
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
