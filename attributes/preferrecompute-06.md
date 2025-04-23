---
layout: stdlib-reference
---

# attribute [PreferRecompute]

## Description

Mark a differentiable function to prefer recomputation over checkpointing when a value computed in the primal pass is needed
during backward derivative propagation.


## Signature

<pre>
[<a href="preferrecompute-06.md">PreferRecompute</a>(<a href="preferrecompute-06.md#decl-behavior" class="code_param">behavior</a> : <a href="../types/sideeffectbehavior-04a/index.md" class="code_type">SideEffectBehavior</a>)]
</pre>

## Parameters

####  <a id="decl-behavior"></a>behavior  : [SideEffectBehavior](../types/sideeffectbehavior-04a/index.md) = [SideEffectBehavior](../types/sideeffectbehavior-04a/index.md)\.[Warn](../types/sideeffectbehavior-04a/index.md#decl-Warn)


<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
