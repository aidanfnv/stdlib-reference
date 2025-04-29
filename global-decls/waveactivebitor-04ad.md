---
layout: stdlib-reference
---

# WaveActiveBitOr

## Description





## Signature 

<pre>
<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a> <a href="waveactivebitor-04ad.html">WaveActiveBitOr</a>&lt;<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a>&gt;(<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a> <a href="waveactivebitor-04ad.html#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinIntegerType</a>;

<a href="index.html" class="code_type">vector</a>&lt;<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a>, <a href="waveactivebitor-04ad.html#decl-N" class="code_var">N</a>&gt; <a href="waveactivebitor-04ad.html">WaveActiveBitOr</a>&lt;<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a>, <a href="waveactivebitor-04ad.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">vector</a>&lt;<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a>, <a href="waveactivebitor-04ad.html#decl-N" class="code_var">N</a>&gt; <a href="waveactivebitor-04ad.html#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinIntegerType</a>;

<a href="index.html" class="code_type">matrix</a>&lt;<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a>, <a href="waveactivebitor-04ad.html#decl-N" class="code_var">N</a>, <a href="waveactivebitor-04ad.html#decl-M" class="code_var">M</a>&gt; <a href="waveactivebitor-04ad.html">WaveActiveBitOr</a>&lt;<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a>, <a href="waveactivebitor-04ad.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="waveactivebitor-04ad.html#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">matrix</a>&lt;<a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a>, <a href="waveactivebitor-04ad.html#decl-N" class="code_var">N</a>, <a href="waveactivebitor-04ad.html#decl-M" class="code_var">M</a>&gt; <a href="waveactivebitor-04ad.html#decl-expr" class="code_param">expr</a>)
    <span class='code_keyword'>where</span> <a href="waveactivebitor-04ad.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">__BuiltinIntegerType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-expr"></a>expr  : [T](waveactivebitor-04ad#typeparam-T)
####  <a id="decl-expr"></a>expr  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
####  <a id="decl-expr"></a>expr  : [matrix](../types/matrix/index)\<[T](../types/matrix/t-0), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.

Requires capability: `spvGroupNonUniformArithmetic`.


