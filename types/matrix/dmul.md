---
layout: stdlib-reference
---

# matrix\<T,R,C\>\.dmul

## Description





## Signature 

<pre>
<span class='code_keyword'>static</span> <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="" class="code_type">T</a>, <a href="../types/matrix/index#decl-N" class="code_var">N</a>, <a href="../types/matrix/index#decl-M" class="code_var">M</a>&gt; <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="" class="code_type">T</a>, <a href="../types/matrix/index#decl-R" class="code_var">R</a>, <a href="../types/matrix/index#decl-C" class="code_var">C</a>&gt;.<a href="dmul">dmul</a>&lt;<a href="dmul#typeparam-U" class="code_type">U</a>&gt;(
    <a href="dmul#typeparam-U" class="code_type">U</a> <a href="dmul#decl-a" class="code_param">a</a>,
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="" class="code_type">T</a>, <a href="../types/matrix/index#decl-N" class="code_var">N</a>, <a href="../types/matrix/index#decl-M" class="code_var">M</a>&gt; <a href="dmul#decl-b" class="code_param">b</a>)
    <span class='code_keyword'>where</span> <a href="dmul#typeparam-U" class="code_type">U</a> : __BuiltinRealType
    <span class='code_keyword'>where</span> <a href="" class="code_type">T</a> : <a href="../interfaces/idifferentiable-01/index" class="code_type">IDifferentiable</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: \_\_BuiltinRealType

## Parameters

####  <a id="decl-a"></a>a  : [U](dmul#typeparam-U)
####  <a id="decl-b"></a>b  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>

