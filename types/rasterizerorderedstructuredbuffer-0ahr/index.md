---
layout: stdlib-reference
---

# struct RasterizerOrderedStructuredBuffer\<T, L\>

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>, [IRWArray](../interfaces/irwarray-0123/index)\<[T](../interfaces/irwarray-0123/index#typeparam-T)\>

## Description

Represents an opaque handle to a mutable structured buffer allocated in global memory.
A structured buffer can be viewed as an array of the specified element type.

## Generic Parameters

####  <a id="typeparam-T"></a>T
The element type of the buffer.

####  <a id="typeparam-L"></a>L: [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index) = [DefaultDataLayout](../types/defaultdatalayout-07b/index)
The memory layout of the buffer.


## Fields

####  <a id="decl-kind"></a>[kind]() : [DescriptorKind](../types/descriptorkind-0a/index) = [DescriptorKind](../types/descriptorkind-0a/index)\.[Buffer](../types/descriptorkind-0a/index#decl-Buffer)

## Methods

* [DecrementCounter](../decrementcounter-09)
* [GetDimensions](../getdimensions-03)
* [IncrementCounter](../incrementcounter-09)
* [Load](../load-0)
* operator\[\]
* [init](../init)
* [getCount](../getcount-3)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`RasterizerOrderedStructuredBuffer<T, L>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>` when the following conditions are met:

  * [L](index#typeparam-L) : [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index)
### Conformance to IRWArray\<T\>
`RasterizerOrderedStructuredBuffer<T, L>` additionally conforms to `IRWArray\<T\>` when the following conditions are met:

  * [L](index#typeparam-L) : [IBufferDataLayout](../interfaces/ibufferdatalayout-017b/index)
## Remarks


The <span class='code'><a href="index#typeparam-L" class="code_type">L</a></span> generic parameter is used to specify the memory layout of the buffer when
generating SPIRV.
<span class='code'><a href="index#typeparam-L" class="code_type">L</a></span> must be one of <span class='code'><a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a></span>, <span class='code'><a href="../types/std140datalayout-06a/index" class="code_type">Std140DataLayout</a></span>, <span class='code'><a href="../types/std430datalayout-06a/index" class="code_type">Std430DataLayout</a></span> or <span class='code'><a href="../types/scalardatalayout-06a/index" class="code_type">ScalarDataLayout</a></span>.
The default value is <span class='code'><a href="../types/defaultdatalayout-07b/index" class="code_type">DefaultDataLayout</a></span>.
When generating code for other targets, this parameter is ignored and has no effect on the generated code.

## See also

<span class='code'><a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a></span>, <span class='code'><a href="../types/appendstructuredbuffer-06g/index" class="code_type">AppendStructuredBuffer</a></span>, <span class='code'><a href="../types/consumestructuredbuffer-07h/index" class="code_type">ConsumeStructuredBuffer</a></span>
*



```{toctree}
:titlesonly:
:hidden:

DecrementCounter <decrementcounter-09>
GetDimensions <getdimensions-03>
Handle <handle-0>
IncrementCounter <incrementcounter-09>
Load <load-0>
getCount <getcount-3>
init <init>
kind <kind>
subscript <subscript>
```
