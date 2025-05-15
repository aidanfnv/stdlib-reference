---
layout: stdlib-reference
---

# linalg\.TensorLayout\<Dim, ClampMode\>\.ClampValue

## Description





## Signature 

<pre>
linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;1, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt; linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;<a href="index.html#decl-Dim" class="code_var">Dim</a>, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt;.<a href="clampvalue-05.html">ClampValue</a>(
    linalg.<a href="../coopmatclampmode-047c/index.html" class="code_type">CoopMatClampMode</a> <a href="clampvalue-05.html#decl-clampMode" class="code_param">clampMode</a>)
    <span class='code_keyword'>where</span> <a href="index.html#decl-Dim" class="code_var">Dim</a> == 1;

linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;2, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt; linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;<a href="index.html#decl-Dim" class="code_var">Dim</a>, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt;.<a href="clampvalue-05.html">ClampValue</a>(
    linalg.<a href="../coopmatclampmode-047c/index.html" class="code_type">CoopMatClampMode</a> <a href="clampvalue-05.html#decl-clampMode" class="code_param">clampMode</a>)
    <span class='code_keyword'>where</span> <a href="index.html#decl-Dim" class="code_var">Dim</a> == 2;

linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;3, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt; linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;<a href="index.html#decl-Dim" class="code_var">Dim</a>, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt;.<a href="clampvalue-05.html">ClampValue</a>(
    linalg.<a href="../coopmatclampmode-047c/index.html" class="code_type">CoopMatClampMode</a> <a href="clampvalue-05.html#decl-clampMode" class="code_param">clampMode</a>)
    <span class='code_keyword'>where</span> <a href="index.html#decl-Dim" class="code_var">Dim</a> == 3;

linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;4, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt; linalg.<a href="index.html" class="code_type">TensorLayout</a>&lt;<a href="index.html#decl-Dim" class="code_var">Dim</a>, <a href="index.html#decl-ClampMode" class="code_var">ClampMode</a>&gt;.<a href="clampvalue-05.html">ClampValue</a>(
    linalg.<a href="../coopmatclampmode-047c/index.html" class="code_type">CoopMatClampMode</a> <a href="clampvalue-05.html#decl-clampMode" class="code_param">clampMode</a>)
    <span class='code_keyword'>where</span> <a href="index.html#decl-Dim" class="code_var">Dim</a> == 4;

</pre>

## Parameters

####  <a id="decl-clampMode"></a>clampMode  : linalg\.[CoopMatClampMode](../coopmatclampmode-047c/index.html)

## Availability and Requirements

Defined for the following targets:

#### spirv
Available in all stages.

Requires capability: `spvTensorAddressingNV`.


