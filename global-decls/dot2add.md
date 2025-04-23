---
layout: stdlib-reference
---

# dot2add

## Description

Computes <span class='code'><a href="dot.md">dot</a>(<a href="dot.md#decl-x" class="code_param">x</a>, <a href="dot.md#decl-y" class="code_param">y</a>)+acc</span>.
May not produce infinities or NaNs for intermediate results that overflow the range of <span class='code'><span class="code_keyword">half</span></span>




## Signature 

<pre>
<span class="code_keyword">float</span> <a href="dot2add.md">dot2add</a>(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, 2&gt; <a href="dot2add.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, 2&gt; <a href="dot2add.md#decl-y" class="code_param">y</a>,
    <span class="code_keyword">float</span> <a href="dot2add.md#decl-acc" class="code_param">acc</a>);

</pre>

## Parameters

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<half, 2\>
####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<half, 2\>
####  <a id="decl-acc"></a>acc  : float

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.

Requires capabilities: `SPV_KHR_non_semantic_info`, `SPV_GOOGLE_user_type`, `spvDerivativeControl`, `spvImageQuery`, `spvImageGatherExtended`, `spvSparseResidency`, `spvMinLod`, `spvFragmentBarycentricKHR`, `spvFragmentFullyCoveredEXT`, `spvGroupNonUniformBallot`, `spvGroupNonUniformShuffle`, `spvGroupNonUniformArithmetic`, `spvGroupNonUniformQuad`, `spvGroupNonUniformVote`, `spvRayTracingPositionFetchKHR`, `spvShaderNonUniformEXT`.



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
