---
layout: stdlib-reference
---

# interface ILogical

*Inherits from:* [IComparable](../icomparable-01/index.md)

## Description

Represents types that provide logical operations.


## Methods

* [shl](shl.md)
* [shr](shr.md)
* [bitAnd](bitand-3.md)
* [bitOr](bitor-3.md)
* [bitXor](bitxor-3.md)
* [bitNot](bitnot-3.md)
* [and](and.md)
* [or](or.md)
* [not](not.md)
* [init](init.md)


```{toctree}
:titlesonly:
:hidden:

and <../interfaces/ilogical-01/and>
bitAnd <../interfaces/ilogical-01/bitand-3>
bitNot <../interfaces/ilogical-01/bitnot-3>
bitOr <../interfaces/ilogical-01/bitor-3>
bitXor <../interfaces/ilogical-01/bitxor-3>
init <../interfaces/ilogical-01/init>
not <../interfaces/ilogical-01/not>
or <../interfaces/ilogical-01/or>
shl <../interfaces/ilogical-01/shl>
shr <../interfaces/ilogical-01/shr>
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
