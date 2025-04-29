---
layout: stdlib-reference
---

# DiffTensorView\<T, A\>\.store

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="store">store</a>(
    <span class="code_keyword">uint</span> <a href="store#decl-x" class="code_param">x</a>,
    <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="store#decl-val" class="code_param">val</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<span class="code_keyword">void</span> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="store">store</a>&lt;<a href="store#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="store#decl-N" class="code_var">N</a>&gt; <a href="store#decl-x" class="code_param">x</a>,
    <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="store#decl-val" class="code_param">val</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : uint
####  <a id="decl-val"></a>val  : [T](../types/difftensorview-04a/index#typeparam-T)
####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<uint, [N](../types/vector/index#decl-N)\>

