---
layout: stdlib-reference
---

# asuint16

## Description

Reinterpret bits as a uint16_t (HLSL SM 6.2).




## Signature 

<pre>
uint16_t <a href="asuint16.html">asuint16</a>(uint16_t <a href="asuint16.html#decl-value" class="code_param">value</a>);

<a href="index.html" class="code_type">vector</a>&lt;uint16_t, <a href="asuint16.html#decl-N" class="code_var">N</a>&gt; <a href="asuint16.html">asuint16</a>&lt;<a href="asuint16.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">vector</a>&lt;uint16_t, <a href="asuint16.html#decl-N" class="code_var">N</a>&gt; <a href="asuint16.html#decl-value" class="code_param">value</a>);

<a href="index.html" class="code_type">matrix</a>&lt;uint16_t, <a href="asuint16.html#decl-R" class="code_var">R</a>, <a href="asuint16.html#decl-C" class="code_var">C</a>&gt; <a href="asuint16.html">asuint16</a>&lt;<a href="asuint16.html#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="asuint16.html#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">matrix</a>&lt;uint16_t, <a href="asuint16.html#decl-R" class="code_var">R</a>, <a href="asuint16.html#decl-C" class="code_var">C</a>&gt; <a href="asuint16.html#decl-value" class="code_param">value</a>);

uint16_t <a href="asuint16.html">asuint16</a>(int16_t <a href="asuint16.html#decl-value" class="code_param">value</a>);

<a href="index.html" class="code_type">vector</a>&lt;uint16_t, <a href="asuint16.html#decl-N" class="code_var">N</a>&gt; <a href="asuint16.html">asuint16</a>&lt;<a href="asuint16.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">vector</a>&lt;int16_t, <a href="asuint16.html#decl-N" class="code_var">N</a>&gt; <a href="asuint16.html#decl-value" class="code_param">value</a>);

<a href="index.html" class="code_type">matrix</a>&lt;uint16_t, <a href="asuint16.html#decl-R" class="code_var">R</a>, <a href="asuint16.html#decl-C" class="code_var">C</a>&gt; <a href="asuint16.html">asuint16</a>&lt;<a href="asuint16.html#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="asuint16.html#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">matrix</a>&lt;int16_t, <a href="asuint16.html#decl-R" class="code_var">R</a>, <a href="asuint16.html#decl-C" class="code_var">C</a>&gt; <a href="asuint16.html#decl-value" class="code_param">value</a>);

uint16_t <a href="asuint16.html">asuint16</a>(<span class="code_keyword">half</span> <a href="asuint16.html#decl-value" class="code_param">value</a>);

<a href="index.html" class="code_type">vector</a>&lt;uint16_t, <a href="asuint16.html#decl-N" class="code_var">N</a>&gt; <a href="asuint16.html">asuint16</a>&lt;<a href="asuint16.html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, <a href="asuint16.html#decl-N" class="code_var">N</a>&gt; <a href="asuint16.html#decl-value" class="code_param">value</a>);

<a href="index.html" class="code_type">matrix</a>&lt;uint16_t, <a href="asuint16.html#decl-R" class="code_var">R</a>, <a href="asuint16.html#decl-C" class="code_var">C</a>&gt; <a href="asuint16.html">asuint16</a>&lt;<a href="asuint16.html#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="asuint16.html#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="index.html" class="code_type">matrix</a>&lt;<span class="code_keyword">half</span>, <a href="asuint16.html#decl-R" class="code_var">R</a>, <a href="asuint16.html#decl-C" class="code_var">C</a>&gt; <a href="asuint16.html#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int
####  <a id="decl-R"></a>R  : int
####  <a id="decl-C"></a>C  : int

## Parameters

####  <a id="decl-value"></a>value  : uint16\_t
####  <a id="decl-value"></a>value  : [vector](../types/vector/index)\<uint16\_t, [N](../types/vector/index#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index)\<uint16\_t, [R](../types/matrix/index#decl-R), [C](../types/matrix/index#decl-C)\>
####  <a id="decl-value"></a>value  : int16\_t
####  <a id="decl-value"></a>value  : [vector](../types/vector/index)\<int16\_t, [N](../types/vector/index#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index)\<int16\_t, [R](../types/matrix/index#decl-R), [C](../types/matrix/index#decl-C)\>
####  <a id="decl-value"></a>value  : half
####  <a id="decl-value"></a>value  : [vector](../types/vector/index)\<half, [N](../types/vector/index#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../types/matrix/index)\<half, [R](../types/matrix/index#decl-R), [C](../types/matrix/index#decl-C)\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.



