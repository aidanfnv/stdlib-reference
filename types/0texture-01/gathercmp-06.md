---
layout: stdlib-reference
---

# \_Texture\<T, Shape, isArray, isMS, sampleCount, access, isShadow, isCombined, format\>\.GatherCmp

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="gathercmp-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="gathercmp-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="gathercmp-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="gathercmp-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="gathercmp-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="gathercmp-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="gathercmp-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset1" class="code_param">offset1</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset2" class="code_param">offset2</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset3" class="code_param">offset3</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset4" class="code_param">offset4</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/samplercomparisonstate-07h/index" class="code_type">SamplerComparisonState</a> <a href="gathercmp-06#decl-s" class="code_param">s</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset1" class="code_param">offset1</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset2" class="code_param">offset2</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset3" class="code_param">offset3</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset4" class="code_param">offset4</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="gathercmp-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 0;

/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="gathercmp-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset" class="code_param">offset</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset" class="code_param">offset</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="gathercmp-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset1" class="code_param">offset1</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset2" class="code_param">offset2</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset3" class="code_param">offset3</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset4" class="code_param">offset4</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

/// Requires Capability Set 2:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element, 4&gt; <a href="../types/0texture-01/index" class="code_type">_Texture</a>&lt;<a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>, <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a>, <a href="../types/0texture-01/index#decl-sampleCount" class="code_var">sampleCount</a>, <a href="../types/0texture-01/index#decl-access" class="code_var">access</a>, <a href="../types/0texture-01/index#decl-isShadow" class="code_var">isShadow</a>, <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a>, <a href="../types/0texture-01/index#decl-format" class="code_var">format</a>&gt;.<a href="gathercmp-06">GatherCmp</a>(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="../types/0texture-01/index#decl-isArray" class="code_var">isArray</a>+<a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.dimensions&gt; <a href="gathercmp-06#decl-location" class="code_param">location</a>,
    <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a>.Element <a href="gathercmp-06#decl-compareValue" class="code_param">compareValue</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset1" class="code_param">offset1</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset2" class="code_param">offset2</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset3" class="code_param">offset3</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a>.planeDimensions&gt; <a href="gathercmp-06#decl-offset4" class="code_param">offset4</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="gathercmp-06#decl-status" class="code_param">status</a>)
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/itexelelement-016/index" class="code_type">ITexelElement</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#typeparam-Shape" class="code_type">Shape</a> : <a href="../interfaces/0_itextureshape-023a/index" class="code_type">__ITextureShape</a>
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isMS" class="code_var">isMS</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-access" class="code_var">access</a> == 0
    <span class='code_keyword'>where</span> <a href="../types/0texture-01/index#decl-isCombined" class="code_var">isCombined</a> == 1;

</pre>

## Parameters

####  <a id="decl-s"></a>s  : [SamplerComparisonState](../types/samplercomparisonstate-07h/index)
####  <a id="decl-location"></a>location  : [vector](../types/vector/index)\<float, isArray + Shape\.dimensions\>
####  <a id="decl-compareValue"></a>compareValue  : [T](../types/0texture-01/index#typeparam-T)\.Element
####  <a id="decl-status"></a>status  : uint
####  <a id="decl-offset"></a>offset  : [vector](../types/vector/index)\<int, Shape\.planeDimensions\>
####  <a id="decl-offset1"></a>offset1  : [vector](../types/vector/index)\<int, Shape\.planeDimensions\>
####  <a id="decl-offset2"></a>offset2  : [vector](../types/vector/index)\<int, Shape\.planeDimensions\>
####  <a id="decl-offset3"></a>offset3  : [vector](../types/vector/index)\<int, Shape\.planeDimensions\>
####  <a id="decl-offset4"></a>offset4  : [vector](../types/vector/index)\<int, Shape\.planeDimensions\>

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvImageGatherExtended`.

### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.



