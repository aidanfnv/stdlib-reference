---
layout: stdlib-reference
---

# AtomicAdd\.loadOnce\_backward

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../index.html" class="code_type">AtomicAdd</a>.<a href=".html">loadOnce_backward</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">uint</span> <a href=".html#decl-i" class="code_param">i</a>,
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-dOut" class="code_param">dOut</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

<span class="code_keyword">void</span> <a href="../index.html" class="code_type">AtomicAdd</a>.<a href=".html">loadOnce_backward</a>&lt;<a href=".html#typeparam-T" class="code_type">T</a>, <a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../../vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-i" class="code_param">i</a>,
    <a href=".html#typeparam-T" class="code_type">T</a> <a href=".html#decl-dOut" class="code_param">dOut</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../../../interfaces/0_builtinfloatingpointtype-029hm/index.html)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-i"></a>i  : uint
####  <a id="decl-dOut"></a>dOut  : [T](.html#typeparam-T)
####  <a id="decl-i"></a>i  : [vector](../../vector/index.html)\<uint, [N](../../vector/index.html#decl-N)\>

