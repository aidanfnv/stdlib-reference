---
layout: stdlib-reference
---

# AppendStructuredBuffer\<T, L\>\.GetDimensions

## Description

Get information about the number of elements and stride of the buffer.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/appendstructuredbuffer-06g/index" class="code_type">AppendStructuredBuffer</a>&lt;<a href="../types/appendstructuredbuffer-06g/index#typeparam-T" class="code_type">T</a>, <a href="../types/appendstructuredbuffer-06g/index#typeparam-L" class="code_type">L</a>&gt;.<a href="getdimensions-03">GetDimensions</a>(
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03#decl-numStructs" class="code_param">numStructs</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href="getdimensions-03#decl-stride" class="code_param">stride</a>)
    <span class='code_keyword'>where</span> <a href="../types/appendstructuredbuffer-06g/index#typeparam-L" class="code_type">L</a> : <a href="../interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

</pre>

## Parameters

####  <a id="decl-numStructs"></a>numStructs  : uint
The number of elements in the buffer.

####  <a id="decl-stride"></a>stride  : uint
The stride of the buffer.


