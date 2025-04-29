---
layout: stdlib-reference
---

# RWStructuredBuffer\<T, L\>\.GetDimensions

## Description

Get the dimensions of the buffer.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/rwstructuredbuffer-012c/index" class="code_type">RWStructuredBuffer</a>&lt;<a href="../types/rwstructuredbuffer-012c/index#typeparam-T" class="code_type">T</a>, <a href="../types/rwstructuredbuffer-012c/index#typeparam-L" class="code_type">L</a>&gt;.<a href="getdimensions-03">GetDimensions</a>(
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03#decl-numStructs" class="code_param">numStructs</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03#decl-stride" class="code_param">stride</a>)
    <span class='code_keyword'>where</span> <a href="../types/rwstructuredbuffer-012c/index#typeparam-L" class="code_type">L</a> : <a href="../interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

</pre>

## Parameters

####  <a id="decl-numStructs"></a>numStructs  : uint
The number of structures in the buffer.

####  <a id="decl-stride"></a>stride  : uint
The stride, in bytes, of each structure element.


## Availability and Requirements

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



