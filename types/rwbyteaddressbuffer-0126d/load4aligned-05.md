---
layout: stdlib-reference
---

# RWByteAddressBuffer\.Load4Aligned

## Description

Load four 32-bit unsigned integers from the buffer at the specified location with alignment
of <span class='code'>uint4</span>, which is 16.



## Signature 

<pre>
<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="../types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a>.<a href="load4aligned-05">Load4Aligned</a>(<span class="code_keyword">int</span> <a href="load4aligned-05#decl-location" class="code_param">location</a>);

</pre>

## Parameters

####  <a id="decl-location"></a>location  : int
The input address in bytes which must be a multiple of alignment of 16.


## Return value
<span class='code'>uint4</span> Four 32-bit unsigned integer value loaded from the buffer.


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

#### spirv
Available in all stages.



