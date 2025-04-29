---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.subscript

## Description





## Signature 

<pre>
<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="subscript#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="subscript#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="subscript#decl-location" class="code_param">location</a>,
    <span class="code_keyword">int</span> <a href="subscript#decl-sampleIndex" class="code_param">sampleIndex</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="subscript#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="subscript#decl-location" class="code_param">location</a>,
    <span class="code_keyword">int</span> <a href="subscript#decl-sampleIndex" class="code_param">sampleIndex</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="subscript#decl-location" class="code_param">location</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 3
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> == <a href="../types/0_shapebuffer-027/index" class="code_type">__ShapeBuffer</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> == <a href="../types/0_shapebuffer-027/index" class="code_type">__ShapeBuffer</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 1
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="subscript">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> == <a href="../types/0_shapebuffer-027/index" class="code_type">__ShapeBuffer</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 2
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

</pre>

## Parameters

####  <a id="decl-location"></a>location  : [vector](../types/vector/index)\<uint, isArray + Shape\.dimensions\>
####  <a id="decl-sampleIndex"></a>sampleIndex  : int
####  <a id="decl-index"></a>index  : uint

