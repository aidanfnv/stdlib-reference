---
layout: stdlib-reference
---

# attribute [BackwardDifferentiable]

## Description

Marks a function as being differentiable for backward-mode auto-diff.
Note that in the current implementation, this implies that the method
is also forward differentiable.

This attribute is equivalent to using <span class='code'>[<a href="differentiable-0.md">Differentiable</a>]</span>


## Signature

<pre>
[<a href="backwarddifferentiable-08.md">BackwardDifferentiable</a>(<a href="backwarddifferentiable-08.md#decl-order" class="code_param">order</a> : <span class="code_keyword">int</span>)]
</pre>

## Parameters

####  <a id="decl-order"></a>order  : int = 0


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
