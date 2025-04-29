---
layout: stdlib-reference
---

# AtomicAdd\.loadOnce\_backward

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/atomicadd-06/index" class="code_type">AtomicAdd</a>.<a href="loadonce_backward-4">loadOnce_backward</a>&lt;<a href="loadonce_backward-4#typeparam-T" class="code_type">T</a>&gt;(
    <span class="code_keyword">uint</span> <a href="loadonce_backward-4#decl-i" class="code_param">i</a>,
    <a href="loadonce_backward-4#typeparam-T" class="code_type">T</a> <a href="loadonce_backward-4#decl-dOut" class="code_param">dOut</a>)
    <span class='code_keyword'>where</span> <a href="loadonce_backward-4#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

<span class="code_keyword">void</span> <a href="../types/atomicadd-06/index" class="code_type">AtomicAdd</a>.<a href="loadonce_backward-4">loadOnce_backward</a>&lt;<a href="loadonce_backward-4#typeparam-T" class="code_type">T</a>, <a href="loadonce_backward-4#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="loadonce_backward-4#decl-N" class="code_var">N</a>&gt; <a href="loadonce_backward-4#decl-i" class="code_param">i</a>,
    <a href="loadonce_backward-4#typeparam-T" class="code_type">T</a> <a href="loadonce_backward-4#decl-dOut" class="code_param">dOut</a>)
    <span class='code_keyword'>where</span> <a href="loadonce_backward-4#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index)
####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-i"></a>i  : uint
####  <a id="decl-dOut"></a>dOut  : [T](loadonce_backward-4#typeparam-T)
####  <a id="decl-i"></a>i  : [vector](../types/vector/index)\<uint, [N](../types/vector/index#decl-N)\>

