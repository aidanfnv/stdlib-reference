---
layout: stdlib-reference
---

# interface IMutatingFunc\<TR, each TP\>

## Description

Represents an interface for a mutating function that can take multiple parameters.
The function allows to modify the state of the object it belongs to.


## Generic Parameters

####  <a id="typeparam-TR"></a>TR
####  <a id="typeparam-TP"></a>TP

## Methods

* [operator\(\)](operatorx28x29.md)


```{toctree}
:titlesonly:
:hidden:

operator() <../interfaces/imutatingfunc-019/operatorx28x29>
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
