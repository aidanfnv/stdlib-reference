---
layout: stdlib-reference
---

# typealias Texture2DMS\<T, int sampleCount, int format\>

## Description

Represents a handle to a read-only, multisampled 2D texture.

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="texture2dms-089a.html" class="code_type">Texture2DMS</a>&lt;T, <span class="code_keyword">int</span> sampleCount, <span class="code_keyword">int</span> format&gt; = 
    <a href="0texture-01/index.html" class="code_type">_Texture</a>&lt;T, <a href="0_shape2d-028/index.html" class="code_type">__Shape2D</a>, 0, 1, sampleCount, 0, 0, 0, format&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [ITexelElement](../interfaces/itexelelement-016/index.html) = [vector](vector/index.html)\<float, 4\>
The texel type of the texture.

####  <a id="decl-sampleCount"></a>sampleCount  : int = 0
The number of samples in the texture, when the texture is multisampled.

####  <a id="decl-format"></a>format  : int = 0
The storage format of the texture.


## See also

Please refer to <span class='code'><a href="0texture-01/index.html" class="code_type">_Texture</a></span> for more information about texture types.


