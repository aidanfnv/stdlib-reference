---
layout: stdlib-reference
---

# attribute [ForwardDifferentiable]

## Description

Marks a function as being differentiable in forward-mode.

See the user guide [section on forward-mode differentiation](https://shader-slang.org/slang/user-guide/autodiff.html#invoking-auto-diff-in-slang) for more

If used on a function that has a definition (i.e. a function body),Slang will use
automatic-differentiation to generate a forward-mode derivative of this function,
unless an implementation is provided by the user via <span class='code'>[<a href="forwardderivative-07.md">ForwardDerivative</a>(fn)]</span>

If used on an interface requirement, the signature of the requirement is modified to
include forward-differentiability. Any satisfying method must also be forward-differentiable,
or provide an appropriate derivative implementation.
See the user guide [section on auto-diff for interfaces](https://shader-slang.org/slang/user-guide/autodiff.html##using-auto-diff-with-interface-requirements-and-interface-types) for more


## Signature

<pre>
[<a href="forwarddifferentiable-07.md">ForwardDifferentiable</a>]
</pre>


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
