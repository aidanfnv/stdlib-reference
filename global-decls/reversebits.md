---
layout: stdlib-reference
---

# reversebits

## Description

Reverse order of bits.



## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/reversebits">reversebits</a>(<span class="code_keyword">uint</span> <a href="/stdlib-reference/global-decls/reversebits#decl-value" class="code_param">value</a>);

<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="/stdlib-reference/global-decls/reversebits#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/reversebits">reversebits</a>&lt;<a href="/stdlib-reference/global-decls/reversebits#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="/stdlib-reference/types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="/stdlib-reference/global-decls/reversebits#decl-N" class="code_var">N</a>&gt; <a href="/stdlib-reference/global-decls/reversebits#decl-value" class="code_param">value</a>);

</pre>

## Generic Parameters

#### N  : int {#decl-N}

## Parameters

#### value  : uint {#decl-value}
The value to reverse bits of.

#### value  : [vector](/stdlib-reference/types/vector/index)\<uint, [N](/stdlib-reference/types/vector/index#decl-N)\> {#decl-value}
The value to reverse bits of.


## Return value
The bits of <span class='code'><a href="/stdlib-reference/global-decls/reversebits#decl-value" class="code_param">value</a></span>, reversed such that bit n of the result is equal to bit (width - 1 - n) of <span class='code'><a href="/stdlib-reference/global-decls/reversebits#decl-value" class="code_param">value</a></span>.

## Remarks
For SPIR-V, this function maps to <span class='code'>OpBitReverse</span>.


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



