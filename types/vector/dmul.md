---
layout: stdlib-reference
---

# vector\<T,N\>\.dmul

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/vector/index#typeparam-T" class="code_type">T</a>, <a href="../types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/vector/index#typeparam-T" class="code_type">T</a>, <a href="../types/vector/index#decl-N" class="code_var">N</a>&gt;.<a href="dmul">dmul</a>&lt;<a href="dmul#typeparam-U" class="code_type">U</a>&gt;(
    <a href="dmul#typeparam-U" class="code_type">U</a> <a href="dmul#decl-a" class="code_param">a</a>,
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="../types/vector/index#typeparam-T" class="code_type">T</a>, <a href="../types/vector/index#decl-N" class="code_var">N</a>&gt; <a href="dmul#decl-b" class="code_param">b</a>)
    <span class='code_keyword'>where</span> <a href="dmul#typeparam-U" class="code_type">U</a> : __BuiltinRealType
    <span class='code_keyword'>where</span> <a href="../types/vector/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/idifferentiable-01/index" class="code_type">IDifferentiable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: \_\_BuiltinRealType

## Parameters

####  <a id="decl-a"></a>a  : [U](dmul#typeparam-U)
####  <a id="decl-b"></a>b  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>

