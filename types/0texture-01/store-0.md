---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.Store

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="store-0.md">Store</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="store-0.md#decl-location" class="code_param">location</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="store-0.md#decl-newValue" class="code_param">newValue</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="store-0.md">Store</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="store-0.md#decl-location" class="code_param">location</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="store-0.md#decl-newValue" class="code_param">newValue</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

<span class="code_keyword">void</span> <a href="index.md" class="code_type">_Texture</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>, <a href="index.md#typeparam-Shape" class="code_type">Shape</a>, <a href="index.md#decl-isArray" class="code_var">isArray</a>, <a href="index.md#decl-isMS" class="code_var">isMS</a>, <a href="index.md#decl-sampleCount" class="code_var">sampleCount</a>, <a href="index.md#decl-access" class="code_var">access</a>, <a href="index.md#decl-isShadow" class="code_var">isShadow</a>, <a href="index.md#decl-isCombined" class="code_var">isCombined</a>, <a href="index.md#decl-format" class="code_var">format</a>&gt;.<a href="store-0.md">Store</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="index.md#decl-isArray" class="code_var">isArray</a>+<a href="index.md#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="store-0.md#decl-location" class="code_param">location</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="store-0.md#decl-newValue" class="code_param">newValue</a>)
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-T" class="code_type">T</a> : <a href="../../interfaces/itexelelement-016/index.md" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="index.md#typeparam-Shape" class="code_type">Shape</a> : <a href="../../interfaces/0_itextureshape-023a/index.md" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="index.md#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="index.md#decl-access" class="code_var">access</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../vector/index.md)\<uint, isArray + Shape\.dimensions\>
####  <a id="decl-newValue"></a>newValue  : [T](index.md#typeparam-T)


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
