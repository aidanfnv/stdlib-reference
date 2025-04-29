---
layout: stdlib-reference
---

# ConsumeStructuredBuffer\<T, L\>\.GetDimensions

## Description

Gets the dimensions of the resource.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/consumestructuredbuffer-07h/index" class="code_type">ConsumeStructuredBuffer</a>&lt;<a href="../types/consumestructuredbuffer-07h/index#typeparam-T" class="code_type">T</a>, <a href="../types/consumestructuredbuffer-07h/index#typeparam-L" class="code_type">L</a>&gt;.<a href="getdimensions-03">GetDimensions</a>(
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03#decl-numStructs" class="code_param">numStructs</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03#decl-stride" class="code_param">stride</a>)
    <span class='code_keyword'>where</span> <a href="../types/consumestructuredbuffer-07h/index#typeparam-L" class="code_type">L</a> : <a href="../interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

</pre>

## Parameters

####  <a id="decl-numStructs"></a>numStructs  : uint
\[out\] The number of structures in the buffer.

####  <a id="decl-stride"></a>stride  : uint
\[out\] The stride, in bytes, of each element


