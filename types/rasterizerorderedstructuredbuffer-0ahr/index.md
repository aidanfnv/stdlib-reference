---
layout: stdlib-reference
---

# struct RasterizerOrderedStructuredBuffer\<T, L\>

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>, [IRWArray](../../interfaces/irwarray-0123/index.md)\<[T](../../interfaces/irwarray-0123/index.md#typeparam-T)\>

## Description

Represents an opaque handle to a mutable structured buffer allocated in global memory.
A structured buffer can be viewed as an array of the specified element type.

## Generic Parameters

####  <a id="typeparam-T"></a>T
The element type of the buffer.

####  <a id="typeparam-L"></a>L: [IBufferDataLayout](../../interfaces/ibufferdatalayout-017b/index.md) = [DefaultDataLayout](../defaultdatalayout-07b/index.md)
The memory layout of the buffer.


## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) = [DescriptorKind](../descriptorkind-0a/index.md)\.[Buffer](../descriptorkind-0a/index.md#decl-Buffer)

## Methods

* [DecrementCounter](decrementcounter-09.md)
* [GetDimensions](getdimensions-03.md)
* [IncrementCounter](incrementcounter-09.md)
* [Load](load-0.md)
* operator\[\]
* [init](init.md)
* [getCount](getcount-3.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`RasterizerOrderedStructuredBuffer<T, L>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>` when the following conditions are met:

  * [L](index.md#typeparam-L) : [IBufferDataLayout](../../interfaces/ibufferdatalayout-017b/index.md)
### Conformance to IRWArray\<T\>
`RasterizerOrderedStructuredBuffer<T, L>` additionally conforms to `IRWArray\<T\>` when the following conditions are met:

  * [L](index.md#typeparam-L) : [IBufferDataLayout](../../interfaces/ibufferdatalayout-017b/index.md)
## Remarks


The <span class='code'><a href="index.md#typeparam-L" class="code_type">L</a></span> generic parameter is used to specify the memory layout of the buffer when
generating SPIRV.
<span class='code'><a href="index.md#typeparam-L" class="code_type">L</a></span> must be one of <span class='code'><a href="../defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a></span>, <span class='code'><a href="../std140datalayout-06a/index.md" class="code_type">Std140DataLayout</a></span>, <span class='code'><a href="../std430datalayout-06a/index.md" class="code_type">Std430DataLayout</a></span> or <span class='code'><a href="../scalardatalayout-06a/index.md" class="code_type">ScalarDataLayout</a></span>.
The default value is <span class='code'><a href="../defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a></span>.
When generating code for other targets, this parameter is ignored and has no effect on the generated code.

## See also

<span class='code'><a href="../structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a></span>, <span class='code'><a href="../appendstructuredbuffer-06g/index.md" class="code_type">AppendStructuredBuffer</a></span>, <span class='code'><a href="../consumestructuredbuffer-07h/index.md" class="code_type">ConsumeStructuredBuffer</a></span>
*



```{toctree}
:titlesonly:
:hidden:

DecrementCounter <../types/rasterizerorderedstructuredbuffer-0ahr/decrementcounter-09>
GetDimensions <../types/rasterizerorderedstructuredbuffer-0ahr/getdimensions-03>
Handle <../types/rasterizerorderedstructuredbuffer-0ahr/handle-0>
IncrementCounter <../types/rasterizerorderedstructuredbuffer-0ahr/incrementcounter-09>
Load <../types/rasterizerorderedstructuredbuffer-0ahr/load-0>
getCount <../types/rasterizerorderedstructuredbuffer-0ahr/getcount-3>
init <../types/rasterizerorderedstructuredbuffer-0ahr/init>
kind <../types/rasterizerorderedstructuredbuffer-0ahr/kind>
subscript <../types/rasterizerorderedstructuredbuffer-0ahr/subscript>
```

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      const href = link.getAttribute('href');
      if (href && href.includes('.md')) {
        // This regex will handle .md links with or without fragment identifiers or query parameters
        link.href = link.href.replace(/(.+)\.md(#[^?]*)?(\?.*)?$/, '$1.html$2$3');
      }
    });
  });
}
</script>
