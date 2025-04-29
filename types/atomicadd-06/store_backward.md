---
layout: stdlib-reference
---

# AtomicAdd\.store\_backward

## Description





## Signature 

<pre>
<a href="store_backward.html#typeparam-T" class="code_type">T</a> <a href="index.html" class="code_type">AtomicAdd</a>.<a href="store_backward.html">store_backward</a>&lt;<a href="store_backward.html#typeparam-T" class="code_type">T</a>&gt;(<span class="code_keyword">uint</span> <a href="store_backward.html#decl-i" class="code_param">i</a>)
    <span class='code_keyword'>where</span> <a href="store_backward.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinFloatingPointType</a>;

<a href="store_backward.html#typeparam-T" class="code_type">T</a> <a href="index.html" class="code_type">AtomicAdd</a>.<a href="store_backward.html">store_backward</a>&lt;<a href="store_backward.html#typeparam-T" class="code_type">T</a>, <a href="store_backward.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="store_backward.html#decl-N" class="code_var">N</a>&gt; <a href="store_backward.html#decl-i" class="code_param">i</a>)
    <span class='code_keyword'>where</span> <a href="store_backward.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-i"></a>i  : uint
####  <a id="decl-i"></a>i  : [vector](../vector/index)\<uint, [N](../vector/index#decl-N)\>

