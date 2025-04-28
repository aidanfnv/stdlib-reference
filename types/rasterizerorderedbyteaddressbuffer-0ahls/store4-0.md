---
layout: stdlib-reference
---

# RasterizerOrderedByteAddressBuffer\.Store4

## Description

Set four values to the buffer at the specified location.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../types/rasterizerorderedbyteaddressbuffer-0ahls/index.html" class="code_type">RasterizerOrderedByteAddressBuffer</a>.<a href="store4-0.html">Store4</a>(
    <span class="code_keyword">uint</span> <a href="store4-0.html#decl-address" class="code_param">address</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="store4-0.html#decl-value" class="code_param">value</a>);

<span class="code_keyword">void</span> <a href="../types/rasterizerorderedbyteaddressbuffer-0ahls/index.html" class="code_type">RasterizerOrderedByteAddressBuffer</a>.<a href="store4-0.html">Store4</a>(
    <span class="code_keyword">uint</span> <a href="store4-0.html#decl-address" class="code_param">address</a>,
    <a href="../types/vector/index.html" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, 4&gt; <a href="store4-0.html#decl-value" class="code_param">value</a>,
    <span class="code_keyword">uint</span> <a href="store4-0.html#decl-alignment" class="code_param">alignment</a>);

</pre>

## Parameters

####  <a id="decl-address"></a>address  : uint
The input address in bytes, which must be a multiple of 4.

####  <a id="decl-value"></a>value  : [vector](../types/vector/index.html)\<uint, 4\>
Four input values.

####  <a id="decl-alignment"></a>alignment  : uint
Specifies the alignment of the location, which must be a multiple of 4.


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

#### spirv
Available in all stages.



