---
layout: stdlib-reference
---

# StructuredBuffer\<T, L\>\.subscript

## Description





## Signature 

<pre>
<a href="../types/structuredbuffer-0a/index#typeparam-T" class="code_type">T</a> <a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a>&lt;<a href="../types/structuredbuffer-0a/index#typeparam-T" class="code_type">T</a>, <a href="../types/structuredbuffer-0a/index#typeparam-L" class="code_type">L</a>&gt;.<a href="subscript">subscript</a>&lt;<a href="subscript#typeparam-TIndex" class="code_type">TIndex</a>&gt;(
    <a href="subscript#typeparam-TIndex" class="code_type">TIndex</a> <a href="subscript#decl-index" class="code_param">index</a>)
    <span class='code_keyword'>where</span> <a href="subscript#typeparam-TIndex" class="code_type">TIndex</a> : <a href="../interfaces/0_builtinintegertype-029g/index" class="code_type">__BuiltinIntegerType</a>
    <span class='code_keyword'>where</span> <a href="../types/structuredbuffer-0a/index#typeparam-L" class="code_type">L</a> : <a href="../interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-TIndex"></a>TIndex: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index)

## Parameters

####  <a id="decl-index"></a>index  : [TIndex](subscript#typeparam-TIndex)

