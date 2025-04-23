---
layout: stdlib-reference
---

# interface IFunc\<TR, each TP\>

*Inherits from:* [IMutatingFunc](../imutatingfunc-019/index.md)\<[TR](../imutatingfunc-019/index.md#typeparam-TR), [TP](../imutatingfunc-019/index.md#typeparam-TP)\>

## Description

Represents an interface for a function that can take multiple parameters.
This interface inherits from <span class='code'><a href="../imutatingfunc-019/index.md" class="code_type">IMutatingFunc</a></span> but is used for non-mutating functions.


## Generic Parameters

####  <a id="typeparam-TR"></a>TR
####  <a id="typeparam-TP"></a>TP

## Methods

* [operator\(\)](operatorx28x29.md)


```{toctree}
:titlesonly:
:hidden:

operator() <../interfaces/ifunc-01/operatorx28x29>
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
