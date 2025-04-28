---
layout: stdlib-reference
---

# CallShader

## Description

Executes a callable shader with the specified payload.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href=".html">CallShader</a>&lt;<a href=".html#typeparam-Payload" class="code_type">Payload</a>&gt;(
    <span class="code_keyword">uint</span> <a href=".html#decl-shaderIndex" class="code_param">shaderIndex</a>,
    <span class="code_keyword">inout</span> <a href=".html#typeparam-Payload" class="code_type">Payload</a> <a href=".html#decl-payload" class="code_param">payload</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-Payload"></a>Payload

## Parameters

####  <a id="decl-shaderIndex"></a>shaderIndex  : uint
Index of the callable shader to execute

####  <a id="decl-payload"></a>payload  : [Payload](.html#typeparam-Payload)
Data structure to pass to and receive from the callable shader


## Remarks
Used to implement dynamic shader calls during ray tracing


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in stages: `closesthit`, `raygen`, `miss`, `callable`.

#### glsl
Available in stages: `closesthit`, `raygen`, `miss`, `callable`.

#### spirv
Available in stages: `closesthit`, `raygen`, `miss`, `callable`.

Requires capability: `spvRayTracingKHR`.


