---
layout: stdlib-reference
---

# attribute [BackwardDerivativeOf]

## Description

<span class='code'>[<a href="backwardderivativeof-08i.md">BackwardDerivativeOf</a>(fn)]</span> is the back-reference version of <span class='code'>[<a href="backwardderivative-08.md">BackwardDerivative</a>(derivFn)]</span>

When used to decorate a function, the decorated function is considered the backward-derivative
implementation of the referenced function <span class='code'>fn</span>.

Apart from this, the semantics of the custom derivative are the same as for
<span class='code'>[<a href="backwardderivative-08.md">BackwardDerivative</a>(derivFn)]</span>


## Signature

<pre>
[<a href="backwardderivativeof-08i.md">BackwardDerivativeOf</a>(<a href="backwardderivativeof-08i.md#decl-function" class="code_param">function</a>)]
</pre>

## Parameters

####  <a id="decl-function"></a>function


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
