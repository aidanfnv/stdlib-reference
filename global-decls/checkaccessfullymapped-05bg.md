---
layout: stdlib-reference
---

# CheckAccessFullyMapped

## Description





## Signature 

<pre>
<span class="code_keyword">bool</span> <a href="checkaccessfullymapped-05bg.md">CheckAccessFullyMapped</a>(<span class="code_keyword">uint</span> <a href="checkaccessfullymapped-05bg.md#decl-status" class="code_param">status</a>);

</pre>

## Parameters

####  <a id="decl-status"></a>status  : uint

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `SPV_KHR_non_semantic_info`, `SPV_GOOGLE_user_type`, `spvDerivativeControl`, `spvImageQuery`, `spvImageGatherExtended`, `spvSparseResidency`, `spvMinLod`, `spvFragmentFullyCoveredEXT`.



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
