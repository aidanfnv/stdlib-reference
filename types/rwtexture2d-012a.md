---
layout: stdlib-reference
---

# typealias RWTexture2D\<T, sampleCount:int, format:int\>

## Description

Represents a handle to a read-write 2D texture.

## Signature

<pre>
<span class='code_keyword'>typealias</span> <a href="rwtexture2d-012a.html" class="code_type">RWTexture2D</a>&lt;T, sampleCount:<span class="code_keyword">int</span>, format:<span class="code_keyword">int</span>&gt; = 
    <a href="index.html" class="code_type">_Texture</a>&lt;T, <a href="index.html" class="code_type">__Shape2D</a>, 0, 0, sampleCount, 1, 0, 0, format&gt;;
</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [ITexelElement](../interfaces/itexelelement-016/index) = [vector](vector/index)\<float, 4\>
The texel type of the texture.

####  <a id="decl-sampleCount"></a>sampleCount  : int = 0
The number of samples in the texture, when the texture is multisampled.

####  <a id="decl-format"></a>format  : int = 0
The storage format of the texture.


## See also

Please refer to <span class='code'><a href="index.html" class="code_type">_Texture</a></span> for more information about texture types.


