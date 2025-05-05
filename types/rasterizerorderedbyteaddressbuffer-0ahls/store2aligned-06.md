---
layout: stdlib-reference
---

# RasterizerOrderedByteAddressBuffer\.Store2Aligned

## Description

Set two values to the buffer at the specified location, the address will be aligned
to the alignment of  <span class='code'>uint2</span>, which is 8.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="/stdlib-reference/types/rasterizerorderedbyteaddressbuffer-0ahls/index" class="code_type">RasterizerOrderedByteAddressBuffer</a>.<a href="/stdlib-reference/types/rasterizerorderedbyteaddressbuffer-0ahls/store2aligned-06">Store2Aligned</a>(
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/rasterizerorderedbyteaddressbuffer-0ahls/store2aligned-06#decl-address" class="code_param">address</a>,
    <a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 2&gt; <a href="/stdlib-reference/types/rasterizerorderedbyteaddressbuffer-0ahls/store2aligned-06#decl-value" class="code_param">value</a>);

</pre>

## Parameters

#### address  : uint {#decl-address}
The input address in bytes, which must be a multiple of 8.

#### value  : [vector](/stdlib-reference/types/vector/index)\<uint, 2\> {#decl-value}
Two input values.


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



