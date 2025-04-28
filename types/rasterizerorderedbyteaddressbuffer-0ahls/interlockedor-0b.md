---
layout: stdlib-reference
---

# RasterizerOrderedByteAddressBuffer\.InterlockedOr

## Description

Perform an atomic or operation at the specified byte
location of the byte address buffer.



## Signature 

<pre>
<span class="code_keyword">void</span> <a href="../index.html" class="code_type">RasterizerOrderedByteAddressBuffer</a>.<a href=".html">InterlockedOr</a>(
    <span class="code_keyword">uint</span> <a href=".html#decl-dest" class="code_param">dest</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-value" class="code_param">value</a>,
    <span class="code_keyword">out</span> <span class="code_keyword">uint</span> <a href=".html#decl-original_value" class="code_param">original_value</a>);

<span class="code_keyword">void</span> <a href="../index.html" class="code_type">RasterizerOrderedByteAddressBuffer</a>.<a href=".html">InterlockedOr</a>(
    <span class="code_keyword">uint</span> <a href=".html#decl-dest" class="code_param">dest</a>,
    <span class="code_keyword">uint</span> <a href=".html#decl-value" class="code_param">value</a>);

</pre>

## Parameters

####  <a id="decl-dest"></a>dest  : uint
The byte address at which to perform the atomic or operation.

####  <a id="decl-value"></a>value  : uint
The operand of the atomic operation.

####  <a id="decl-original_value"></a>original\_value  : uint
The original value at <span class='code'><a href=".html#decl-dest" class="code_param">dest</a></span> before the or operation.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
Available in all stages.



