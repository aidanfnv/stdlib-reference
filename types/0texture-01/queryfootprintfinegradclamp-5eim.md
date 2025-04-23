---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.queryFootprintFineGradClamp

## Description

Query the footprint that would be accessed by a texture sampling operation.

This operation queries the footprint that would be accessed
by a comparable call to:

t.SampleGradClamp(sampler, coords, dx, dy, lodClamp);




## Signature 

<pre>
<a href="../texturefootprint-07/index.md" class="code_type">TextureFootprint</a>&lt;<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="queryfootprintfinegradclamp-5eim.md">queryFootprintFineGradClamp</a>(
    <span class="code_keyword">uint</span> <a href="queryfootprintfinegradclamp-5eim.md#decl-granularity" class="code_param">granularity</a>,
    <a href="../samplerstate-07/index.md" class="code_type">SamplerState</a> <a href="queryfootprintfinegradclamp-5eim.md#decl-sampler" class="code_param">sampler</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="queryfootprintfinegradclamp-5eim.md#decl-coords" class="code_param">coords</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="queryfootprintfinegradclamp-5eim.md#decl-dx" class="code_param">dx</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="queryfootprintfinegradclamp-5eim.md#decl-dy" class="code_param">dy</a>,
    <span class="code_keyword">float</span> <a href="queryfootprintfinegradclamp-5eim.md#decl-lodClamp" class="code_param">lodClamp</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-granularity"></a>granularity  : uint
####  <a id="decl-sampler"></a>sampler  : [SamplerState](../samplerstate-07/index.md)
####  <a id="decl-coords"></a>coords  : [vector](../vector/index.md)\<float, Shape\.dimensions\>
####  <a id="decl-dx"></a>dx  : [vector](../vector/index.md)\<float, Shape\.dimensions\>
####  <a id="decl-dy"></a>dy  : [vector](../vector/index.md)\<float, Shape\.dimensions\>
####  <a id="decl-lodClamp"></a>lodClamp  : float


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
