---
layout: stdlib-reference
---

# DiffTensorView\<T, A\>\.init

## Description





## Signature 

<pre>
<a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="init">init</a>(
    <a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>&gt; <a href="init#decl-primal" class="code_param">primal</a>,
    <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> <a href="init#decl-diff" class="code_param">diff</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

<a href="../types/difftensorview-04a/index" class="code_type">DiffTensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>, <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a>&gt;.<a href="init">init</a>(<a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a>&gt; <a href="init#decl-primal" class="code_param">primal</a>)
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index" class="code_type">__BuiltinFloatingPointType</a>
    <span class='code_keyword'>where</span> <a href="../types/difftensorview-04a/index#typeparam-A" class="code_type">A</a> : <a href="../interfaces/idifftensorwrapper-015b/index" class="code_type">IDiffTensorWrapper</a>;

</pre>

## Parameters

####  <a id="decl-primal"></a>primal  : [TensorView](../types/tensorview-06/index)\<[T](../types/tensorview-06/index#typeparam-T)\>
####  <a id="decl-diff"></a>diff  : [A](../types/difftensorview-04a/index#typeparam-A)

