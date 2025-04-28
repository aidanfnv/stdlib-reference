---
layout: stdlib-reference
---

# DiffTensorView\<T, A\>\.storeOnce

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/difftensorview-04a/index.html" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index.html#typeparam-A" class="code_type">A</a>&gt;.<a href="storeonce-5.html">storeOnce</a>(
    <span class="code_keyword">uint</span> <a href="storeonce-5.html#decl-x" class="code_param">x</a>,
    <a href="../types/difftensorview-04a/index.html#typeparam-T" class="code_type">T</a> <a href="storeonce-5.html#decl-val" class="code_param">val</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index.html#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index.html" class="code_type">IDiffTensorWrapper</a>;

<span class="code_keyword">void</span> <a href="../types/difftensorview-04a/index.html" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index.html#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index.html#typeparam-A" class="code_type">A</a>&gt;.<a href="storeonce-5.html">storeOnce</a>&lt;<a href="storeonce-5.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="storeonce-5.html#decl-N" class="code_var">N</a>&gt; <a href="storeonce-5.html#decl-x" class="code_param">x</a>,
    <a href="../types/difftensorview-04a/index.html#typeparam-T" class="code_type">T</a> <a href="storeonce-5.html#decl-val" class="code_param">val</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.html" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index.html#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index.html" class="code_type">IDiffTensorWrapper</a>;

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : uint
####  <a id="decl-val"></a>val  : [T](../types/difftensorview-04a/index.html#typeparam-T)
####  <a id="decl-x"></a>x  : [vector](../types/vector/index.html)\<uint, [N](../types/vector/index.html#decl-N)\>

