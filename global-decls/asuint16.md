---
layout: stdlib-reference
---

# asuint16

## Description

Reinterpret bits as a uint16_t (HLSL SM 6.2).




## Signature 

<pre>
uint16_t <a href=".html">asuint16</a>(uint16_t <a href=".html#decl-value" class="code_param">value</a>);

<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;uint16_t, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">asuint16</a>&lt;<a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;uint16_t, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-value" class="code_param">value</a>);

<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;uint16_t, <a href=".html#decl-R" class="code_var">R</a>, <a href=".html#decl-C" class="code_var">C</a>&gt; <a href=".html">asuint16</a>&lt;<a href=".html#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href=".html#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;uint16_t, <a href=".html#decl-R" class="code_var">R</a>, <a href=".html#decl-C" class="code_var">C</a>&gt; <a href=".html#decl-value" class="code_param">value</a>);

uint16_t <a href=".html">asuint16</a>(int16_t <a href=".html#decl-value" class="code_param">value</a>);

<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;uint16_t, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">asuint16</a>&lt;<a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;int16_t, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-value" class="code_param">value</a>);

<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;uint16_t, <a href=".html#decl-R" class="code_var">R</a>, <a href=".html#decl-C" class="code_var">C</a>&gt; <a href=".html">asuint16</a>&lt;<a href=".html#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href=".html#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;int16_t, <a href=".html#decl-R" class="code_var">R</a>, <a href=".html#decl-C" class="code_var">C</a>&gt; <a href=".html#decl-value" class="code_param">value</a>);

uint16_t <a href=".html">asuint16</a>(<span class="code_keyword">half</span> <a href=".html#decl-value" class="code_param">value</a>);

<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;uint16_t, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html">asuint16</a>&lt;<a href=".html#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">half</span>, <a href=".html#decl-N" class="code_var">N</a>&gt; <a href=".html#decl-value" class="code_param">value</a>);

<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;uint16_t, <a href=".html#decl-R" class="code_var">R</a>, <a href=".html#decl-C" class="code_var">C</a>&gt; <a href=".html">asuint16</a>&lt;<a href=".html#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href=".html#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(<a href="../../types/matrix/index.html" class="code_type">matrix</a>&lt;<span class="code_keyword">half</span>, <a href=".html#decl-R" class="code_var">R</a>, <a href=".html#decl-C" class="code_var">C</a>&gt; <a href=".html#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int
####  <a id="decl-R"></a>R  : int
####  <a id="decl-C"></a>C  : int

## Parameters

####  <a id="decl-value"></a>value  : uint16\_t
####  <a id="decl-value"></a>value  : [vector](../../types/vector/index.html)\<uint16\_t, [N](../../types/vector/index.html#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../../types/matrix/index.html)\<uint16\_t, [R](../../types/matrix/index.html#decl-R), [C](../../types/matrix/index.html#decl-C)\>
####  <a id="decl-value"></a>value  : int16\_t
####  <a id="decl-value"></a>value  : [vector](../../types/vector/index.html)\<int16\_t, [N](../../types/vector/index.html#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../../types/matrix/index.html)\<int16\_t, [R](../../types/matrix/index.html#decl-R), [C](../../types/matrix/index.html#decl-C)\>
####  <a id="decl-value"></a>value  : half
####  <a id="decl-value"></a>value  : [vector](../../types/vector/index.html)\<half, [N](../../types/vector/index.html#decl-N)\>
####  <a id="decl-value"></a>value  : [matrix](../../types/matrix/index.html)\<half, [R](../../types/matrix/index.html#decl-R), [C](../../types/matrix/index.html#decl-C)\>

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



