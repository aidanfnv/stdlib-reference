---
layout: stdlib-reference
---

# struct ConsumeStructuredBuffer\<T, L\>

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>

## Description

Represents an opaque handle to a consume structured buffer allocated in global memory.
A structured buffer can be viewed as an array of the specified element type.
An append structure buffer internally maintains an atomic counter to keep track of the number of elements in the buffer,
and provide an atomic operation to append a new element to the buffer.

## Generic Parameters

####  <a id="typeparam-T"></a>T
The element type of the buffer.

####  <a id="typeparam-L"></a>L: [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index.html) = [DefaultDataLayout](../types/defaultdatalayout-07b/index.html)
The memory layout of the buffer.


## Fields

####  <a id="decl-kind"></a>[kind](.html) : [DescriptorKind](../types/descriptorkind-0a/index.html) = [DescriptorKind](../types/descriptorkind-0a/index.html)\.[Buffer](../types/descriptorkind-0a/index.html#decl-Buffer)

## Methods

* [Consume](../consume-0.html)
* [GetDimensions](../getdimensions-03.html)
* [init](../init.html)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`ConsumeStructuredBuffer<T, L>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>` when the following conditions are met:

  * [L](index.html#typeparam-L) : [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index.html)
## Remarks


This type is supported natively when targeting HLSL.
When generating code for other targets, this type is translated into a pair or an ordinary <span class='code'><a href="../types/structuredbuffer-0a/index.html" class="code_type">StructuredBuffer</a></span> and
a separate <span class='code'><a href="../types/rwstructuredbuffer-012c/index.html" class="code_type">RWStructuredBuffer</a></span> that holds the atomic counter.
The <span class='code'><a href="index.html#typeparam-L" class="code_type">L</a></span> generic parameter is used to specify the memory layout of the buffer when
generating SPIRV.
<span class='code'><a href="index.html#typeparam-L" class="code_type">L</a></span> must be one of <span class='code'><a href="../types/defaultdatalayout-07b/index.html" class="code_type">DefaultDataLayout</a></span>, <span class='code'><a href="../types/std140datalayout-06a/index.html" class="code_type">Std140DataLayout</a></span>, <span class='code'><a href="../types/std430datalayout-06a/index.html" class="code_type">Std430DataLayout</a></span> or <span class='code'><a href="../types/scalardatalayout-06a/index.html" class="code_type">ScalarDataLayout</a></span>.
The default value is <span class='code'><a href="../types/defaultdatalayout-07b/index.html" class="code_type">DefaultDataLayout</a></span>.
When generating code for other targets, this parameter is ignored and has no effect on the generated code.

## See also

<span class='code'><a href="../types/structuredbuffer-0a/index.html" class="code_type">StructuredBuffer</a></span>, <span class='code'><a href="../types/appendstructuredbuffer-06g/index.html" class="code_type">AppendStructuredBuffer</a></span>, <span class='code'><a href="../types/rwstructuredbuffer-012c/index.html" class="code_type">RWStructuredBuffer</a></span>, <span class='code'><a href="../types/rasterizerorderedstructuredbuffer-0ahr/index.html" class="code_type">RasterizerOrderedStructuredBuffer</a></span>.



```{toctree}
:titlesonly:
:hidden:

Consume <consume-0>
GetDimensions <getdimensions-03>
Handle <handle-0>
init <init>
kind <kind>
```
