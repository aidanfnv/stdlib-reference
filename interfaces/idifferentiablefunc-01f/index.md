---
layout: stdlib-reference
---

# interface IDifferentiableFunc\<TR, each TP\>

*Inherits from:* [IFunc](../ifunc-01/index.md)\<[TR](../ifunc-01/index.md#typeparam-TR), [TP](../ifunc-01/index.md#typeparam-TP)\>, [IDifferentiableMutatingFunc](../idifferentiablemutatingfunc-01fn/index.md)\<[TR](../idifferentiablemutatingfunc-01fn/index.md#typeparam-TR), [TP](../idifferentiablemutatingfunc-01fn/index.md#typeparam-TP)\>

## Description

Represents an interface for a function that can take multiple differentiable parameters and supports differentiation.
This interface inherits from both <span class='code'><a href="../ifunc-01/index.md" class="code_type">IFunc</a></span> and <span class='code'><a href="../idifferentiablemutatingfunc-01fn/index.md" class="code_type">IDifferentiableMutatingFunc</a></span> but is used for non-mutating differentiable functions.


## Generic Parameters

####  <a id="typeparam-TR"></a>TR: [IDifferentiable](../idifferentiable-01/index.md)
####  <a id="typeparam-TP"></a>TP: [IDifferentiable](../idifferentiable-01/index.md)

## Methods

* [operator\(\)](operatorx28x29.md)


```{toctree}
:titlesonly:
:hidden:

operator() <../interfaces/idifferentiablefunc-01f/operatorx28x29>
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
