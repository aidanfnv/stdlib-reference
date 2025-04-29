---
layout: stdlib-reference
---

# asfloat

## Description

Reinterpret bits as a float.




## Signature 

<pre>
/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="asfloat">asfloat</a>(<span class="code_keyword">int</span> <a href="asfloat#decl-x" class="code_param">x</a>);

/// Requires Capability Set 1:
<span class="code_keyword">float</span> <a href="asfloat">asfloat</a>(<span class="code_keyword">uint</span> <a href="asfloat#decl-x" class="code_param">x</a>);

/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>&gt; <a href="asfloat">asfloat</a>&lt;<a href="asfloat#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">int</span>, <a href="asfloat#decl-N" class="code_var">N</a>&gt; <a href="asfloat#decl-x" class="code_param">x</a>);

/// Requires Capability Set 1:
<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>&gt; <a href="asfloat">asfloat</a>&lt;<a href="asfloat#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="asfloat#decl-N" class="code_var">N</a>&gt; <a href="asfloat#decl-x" class="code_param">x</a>);

/// Requires Capability Set 2:
<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>, <a href="asfloat#decl-M" class="code_var">M</a>&gt; <a href="asfloat">asfloat</a>&lt;<a href="asfloat#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="asfloat#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">int</span>, <a href="asfloat#decl-N" class="code_var">N</a>, <a href="asfloat#decl-M" class="code_var">M</a>&gt; <a href="asfloat#decl-x" class="code_param">x</a>);

/// Requires Capability Set 2:
<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>, <a href="asfloat#decl-M" class="code_var">M</a>&gt; <a href="asfloat">asfloat</a>&lt;<a href="asfloat#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="asfloat#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">uint</span>, <a href="asfloat#decl-N" class="code_var">N</a>, <a href="asfloat#decl-M" class="code_var">M</a>&gt; <a href="asfloat#decl-x" class="code_param">x</a>);

<span class="code_keyword">float</span> <a href="asfloat">asfloat</a>(<span class="code_keyword">float</span> <a href="asfloat#decl-x" class="code_param">x</a>);

<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>&gt; <a href="asfloat">asfloat</a>&lt;<a href="asfloat#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>&gt; <a href="asfloat#decl-x" class="code_param">x</a>);

<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>, <a href="asfloat#decl-M" class="code_var">M</a>&gt; <a href="asfloat">asfloat</a>&lt;<a href="asfloat#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="asfloat#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/matrix/index" class="code_type">matrix</a>&lt;<span class="code_keyword">float</span>, <a href="asfloat#decl-N" class="code_var">N</a>, <a href="asfloat#decl-M" class="code_var">M</a>&gt; <a href="asfloat#decl-x" class="code_param">x</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int

## Parameters

####  <a id="decl-x"></a>x  : int
####  <a id="decl-x"></a>x  : uint
####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<int, [N](../types/vector/index#decl-N)\>
####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<uint, [N](../types/vector/index#decl-N)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<int, [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<uint, [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>
####  <a id="decl-x"></a>x  : float
####  <a id="decl-x"></a>x  : [vector](../types/vector/index)\<float, [N](../types/vector/index#decl-N)\>
####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index)\<float, [N](../types/matrix/index#decl-N), [M](../types/matrix/index#decl-M)\>

## Availability and Requirements

### Capability Set 1

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### wgsl
Available in all stages.

#### spirv
Available in all stages.


### Capability Set 2

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.



