---
layout: stdlib-reference
---

# interface IDifferentiablePtrType

> #### Experimental Feature
> The feature described in this page is marked as experimental, and may be subject to change in future releases.
> Users are advised that any code that depend on this feature may not be compilable by future versions of the compiler.

## Description


The <span class='code'><a href="index.md" class="code_type">IDifferentiablePtrType</a></span> interface requires the following definitions.

```csharp
interface IDifferentiablePtrType
{
    associatedtype Differential : IDifferentiablePtrType
        where Differential.Differential == Differential;
}
```

Types that conform to this interface can be used with <span class='code'><a href="../../types/differentialptrpair-0cf/index.md" class="code_type">DifferentialPtrPair</a>&lt;T&gt;</span>
to pass the derivative components to calls to <span class='code'>fwd_diff(fn)</span> or <span class='code'>bwd_diff(fn)</span>

See the auto-diff user guide for more details (https://shader-slang.org/slang/user-guide/autodiff.html#differentiable-ptr-types)


## Associated types

#### _Differential



Constraints:

  - IDifferentiablePtrType\.This\.Differential : IDifferentiablePtrType


## Remarks

Support for this interface is still experimental and subject to change.



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
