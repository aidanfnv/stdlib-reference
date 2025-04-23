---
layout: stdlib-reference
---

# attribute [Differentiable]

## Description

Marks a function as being differentiable for both
forward and backward mode auto-diff.

This attribute is equivalent to using <span class='code'>[<a href="differentiable-0.md">Differentiable</a>]</span>

See the user guide [section on auto-diff invocation](https://shader-slang.org/slang/user-guide/autodiff.html#invoking-auto-diff-in-slang) for more.

If used on a function that has a definition (i.e. a function body), Slang will use
automatic-differentiation to generate the derivative implementations for this function,
unless an implementation is provided by the user via <span class='code'>[<a href="forwardderivative-07.md">ForwardDerivative</a>(fn)]</span> and/or <span class='code'>[<a href="backwardderivative-08.md">BackwardDerivative</a>(fn)]</span>

If used on an interface requirement, the signature of the requirement is modified to
include differentiability. Any satisfying method must also be differentiable,
or provide appropriate derivative implementations.
See the user guide [section on auto-diff for interfaces](https://shader-slang.org/slang/user-guide/autodiff.html##using-auto-diff-with-interface-requirements-and-interface-types) for more


## Signature

<pre>
[<a href="differentiable-0.md">Differentiable</a>(<a href="differentiable-0.md#decl-order" class="code_param">order</a> : <span class="code_keyword">int</span>)]
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
