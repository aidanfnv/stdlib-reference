---
layout: stdlib-reference
---

# HitObject\.LoadLocalRootTableConstant

## Description

Loads a root constant from the local root table referenced by the hit object. Valid if the hit object
represents a hit or a miss. RootConstantOffsetInBytes must be a multiple of 4.




## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="index.md" class="code_type">HitObject</a>.<a href="loadlocalroottableconstant-049di.md">LoadLocalRootTableConstant</a>(<span class="code_keyword">uint</span> <a href="loadlocalroottableconstant-049di.md#decl-RootConstantOffsetInBytes" class="code_param">RootConstantOffsetInBytes</a>);

</pre>

## Parameters

####  <a id="decl-RootConstantOffsetInBytes"></a>RootConstantOffsetInBytes  : uint

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

Requires capability: `hlsl_nvapi`.



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
