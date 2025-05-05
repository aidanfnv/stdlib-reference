---
layout: stdlib-reference
---

# RWByteAddressBuffer\.\_NvInterlockedAddFp16x2

## Description



Maps to the <span class='code'>NvInterlockedAddFp16x2</span> NVAPI function.
Perform 2 16-bit floating point atomic add operations at <span class='code'><a href="/stdlib-reference/types/rwbyteaddressbuffer-0126d/0nvinterlockedaddfp16x2-013eh#decl-byteAddress" class="code_param">byteAddress</a></span>.

## Signature 

<pre>
<span class="code_keyword">uint</span> <a href="/stdlib-reference/types/rwbyteaddressbuffer-0126d/index" class="code_type">RWByteAddressBuffer</a>.<a href="/stdlib-reference/types/rwbyteaddressbuffer-0126d/0nvinterlockedaddfp16x2-013eh">_NvInterlockedAddFp16x2</a>(
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/rwbyteaddressbuffer-0126d/0nvinterlockedaddfp16x2-013eh#decl-byteAddress" class="code_param">byteAddress</a>,
    <span class="code_keyword">uint</span> <a href="/stdlib-reference/types/rwbyteaddressbuffer-0126d/0nvinterlockedaddfp16x2-013eh#decl-fp16x2Value" class="code_param">fp16x2Value</a>);

</pre>

## Parameters

#### byteAddress  : uint {#decl-byteAddress}
The address at which to perform the atomic add operation.

#### fp16x2Value  : uint {#decl-fp16x2Value}
Two 16-bit floating point values are packed into a 32-bit unsigned integer.


## Return value
The 2 16-bit floating point values packed into a 32-bit unsigned integer.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### cuda
Available in all stages.

#### spirv
Available in all stages.



