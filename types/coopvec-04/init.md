---
layout: stdlib-reference
---

# CoopVec\<T, N:int\>\.init

## Description





## Signature 

<pre>
<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href="../index.html#typeparam-T" class="code_type">T</a>, <a href="../index.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href=".html">init</a>()
    <span class='code_keyword'>where</span> <a href="../index.html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href="../index.html#typeparam-T" class="code_type">T</a>, <a href="../index.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href=".html">init</a>(<a href="../index.html#typeparam-T" class="code_type">T</a> <a href=".html#decl-t" class="code_param">t</a>)
    <span class='code_keyword'>where</span> <a href="../index.html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href="../index.html#typeparam-T" class="code_type">T</a>, <a href="../index.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href=".html">init</a>&lt;<a href=".html#typeparam-U" class="code_type">U</a>&gt;(<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href=".html#typeparam-U" class="code_type">U</a>, <a href="../index.html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-other" class="code_param">other</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-U" class="code_type">U</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../index.html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href="../index.html#typeparam-T" class="code_type">T</a>, <a href="../index.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href=".html">init</a>&lt;<span class="code_keyword">each</span> <a href=".html#typeparam-U" class="code_type">U</a>&gt;(<a href=".html#typeparam-U" class="code_type">U</a> <a href=".html#decl-args" class="code_param">args</a>)
    <span class='code_keyword'>where</span> <a href=".html#typeparam-U" class="code_type">U</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>
    <span class='code_keyword'>where</span> <a href="../index.html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href="../index.html#typeparam-T" class="code_type">T</a>, <a href="../index.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href=".html">init</a>(<span class="code_keyword">int</span> <a href=".html#decl-i" class="code_param">i</a>)
    <span class='code_keyword'>where</span> <a href="../index.html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href="../index.html#typeparam-T" class="code_type">T</a>, <a href="../index.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;.<a href=".html">init</a>(<a href="../index.html" class="code_type">CoopVec</a>&lt;<a href="../index.html#typeparam-T" class="code_type">T</a>, <a href="../index.html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-x" class="code_param">x</a>)
    <span class='code_keyword'>where</span> <a href="../index.html#typeparam-T" class="code_type">T</a> : <a href="../../../interfaces/0_builtinarithmetictype-029j/index.html" class="code_type">__BuiltinArithmeticType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U: [\_\_BuiltinArithmeticType](../../../interfaces/0_builtinarithmetictype-029j/index.html)

## Parameters

####  <a id="decl-t"></a>t  : [T](../index.html#typeparam-T)
####  <a id="decl-other"></a>other  : [CoopVec](../index.html)\<U, [N](../index.html#decl-N)\>
####  <a id="decl-args"></a>args  : [U](.html#typeparam-U)
####  <a id="decl-i"></a>i  : int
####  <a id="decl-x"></a>x  : [CoopVec](../index.html)\<[T](../index.html#typeparam-T), [N](../index.html#decl-N)\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvCooperativeVectorNV`.


