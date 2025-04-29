---
layout: stdlib-reference
---

# DiffTensorView\<T, A\>\.subscript

## Description





## Signature 

<pre>
<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript">subscript</a>(<span class="code_keyword">uint</span> <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript">subscript</a>(<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="subscript#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript">subscript</a>(<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 3&gt; <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="subscript#decl-y" class="code_param">y</a>,
    <span class="code_keyword">uint</span> <a href="subscript#decl-z" class="code_param">z</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript">subscript</a>(<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> <a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="subscript">subscript</a>(
    <span class="code_keyword">uint</span> <a href="subscript#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="subscript#decl-y" class="code_param">y</a>,
    <span class="code_keyword">uint</span> <a href="subscript#decl-z" class="code_param">z</a>,
    <span class="code_keyword">uint</span> <a href="subscript#decl-w" class="code_param">w</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

</pre>

## Parameters

####  <a id="decl-index"></a>index  : uint
####  <a id="decl-index"></a>index  : [vector](../types/vector/index)\<uint, 2\>
####  <a id="decl-x"></a>x  : uint
####  <a id="decl-y"></a>y  : uint
####  <a id="decl-index"></a>index  : [vector](../types/vector/index)\<uint, 3\>
####  <a id="decl-z"></a>z  : uint
####  <a id="decl-index"></a>index  : [vector](../types/vector/index)\<uint, 4\>
####  <a id="decl-w"></a>w  : uint

