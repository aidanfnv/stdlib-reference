---
layout: stdlib-reference
---

# WaveShuffle

## Description





## Signature 

<pre>
/// Requires Capability Set 1:
<a href="waveshuffle-04#typeparam-T" class="code_type">T</a> <a href="waveshuffle-04">WaveShuffle</a>&lt;<a href="waveshuffle-04#typeparam-T" class="code_type">T</a>&gt;(
    <a href="waveshuffle-04#typeparam-T" class="code_type">T</a> <a href="waveshuffle-04#decl-value" class="code_param">value</a>,
    <span class="code_keyword">int</span> <a href="waveshuffle-04#decl-lane" class="code_param">lane</a>)
    <span class='code_keyword'>where</span> <a href="waveshuffle-04#typeparam-T" class="code_type">T</a> : __BuiltinType;

/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="waveshuffle-04#typeparam-T" class="code_type">T</a>, <a href="waveshuffle-04#decl-N" class="code_var">N</a>&gt; <a href="waveshuffle-04">WaveShuffle</a>&lt;<a href="waveshuffle-04#typeparam-T" class="code_type">T</a>, <a href="waveshuffle-04#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index" class="code_type">vector</a>&lt;<a href="waveshuffle-04#typeparam-T" class="code_type">T</a>, <a href="waveshuffle-04#decl-N" class="code_var">N</a>&gt; <a href="waveshuffle-04#decl-value" class="code_param">value</a>,
    <span class="code_keyword">int</span> <a href="waveshuffle-04#decl-lane" class="code_param">lane</a>)
    <span class='code_keyword'>where</span> <a href="waveshuffle-04#typeparam-T" class="code_type">T</a> : __BuiltinType;

/// Requires Capability Set 2:
<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="waveshuffle-04#typeparam-T" class="code_type">T</a>, <a href="waveshuffle-04#decl-N" class="code_var">N</a>, <a href="waveshuffle-04#decl-M" class="code_var">M</a>&gt; <a href="waveshuffle-04">WaveShuffle</a>&lt;<a href="waveshuffle-04#typeparam-T" class="code_type">T</a>, <a href="waveshuffle-04#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="waveshuffle-04#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index" class="code_type">matrix</a>&lt;<a href="waveshuffle-04#typeparam-T" class="code_type">T</a>, <a href="waveshuffle-04#decl-N" class="code_var">N</a>, <a href="waveshuffle-04#decl-M" class="code_var">M</a>&gt; <a href="waveshuffle-04#decl-value" class="code_param">value</a>,
    <span class="code_keyword">int</span> <a href="waveshuffle-04#decl-lane" class="code_param">lane</a>)
    <span class='code_keyword'>where</span> <a href="waveshuffle-04#typeparam-T" class="code_type">T</a> : __BuiltinType;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: \_\_BuiltinType
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-value"></a>value  : [T](waveshuffle-04#typeparam-T)
####  <a id="decl-lane"></a>lane  : int
####  <a id="decl-value"></a>value  : [vector](../types/vector/index)\<[T](../types/vector/index#typeparam-T), [N](../types/vector/index#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index)\<[T](), [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>

## Availability and Requirements

### Capability Set 1

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

Requires capability: `spvGroupNonUniformShuffle`.

### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
Available in all stages.



