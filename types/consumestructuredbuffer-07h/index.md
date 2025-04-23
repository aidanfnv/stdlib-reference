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

####  <a id="typeparam-L"></a>L: [IBufferDataLayout](../../interfaces/ibufferdatalayout-017b/index.md) = [DefaultDataLayout](../defaultdatalayout-07b/index.md)
The memory layout of the buffer.


## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) = [DescriptorKind](../descriptorkind-0a/index.md)\.[Buffer](../descriptorkind-0a/index.md#decl-Buffer)

## Methods

* [Consume](consume-0.md)
* [GetDimensions](getdimensions-03.md)
* [init](init.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`ConsumeStructuredBuffer<T, L>` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>` when the following conditions are met:

  * [L](index.md#typeparam-L) : [IBufferDataLayout](../../interfaces/ibufferdatalayout-017b/index.md)
## Remarks


This type is supported natively when targeting HLSL.
When generating code for other targets, this type is translated into a pair or an ordinary <span class='code'><a href="../structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a></span> and
a separate <span class='code'><a href="../rwstructuredbuffer-012c/index.md" class="code_type">RWStructuredBuffer</a></span> that holds the atomic counter.
The <span class='code'><a href="index.md#typeparam-L" class="code_type">L</a></span> generic parameter is used to specify the memory layout of the buffer when
generating SPIRV.
<span class='code'><a href="index.md#typeparam-L" class="code_type">L</a></span> must be one of <span class='code'><a href="../defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a></span>, <span class='code'><a href="../std140datalayout-06a/index.md" class="code_type">Std140DataLayout</a></span>, <span class='code'><a href="../std430datalayout-06a/index.md" class="code_type">Std430DataLayout</a></span> or <span class='code'><a href="../scalardatalayout-06a/index.md" class="code_type">ScalarDataLayout</a></span>.
The default value is <span class='code'><a href="../defaultdatalayout-07b/index.md" class="code_type">DefaultDataLayout</a></span>.
When generating code for other targets, this parameter is ignored and has no effect on the generated code.

## See also

<span class='code'><a href="../structuredbuffer-0a/index.md" class="code_type">StructuredBuffer</a></span>, <span class='code'><a href="../appendstructuredbuffer-06g/index.md" class="code_type">AppendStructuredBuffer</a></span>, <span class='code'><a href="../rwstructuredbuffer-012c/index.md" class="code_type">RWStructuredBuffer</a></span>, <span class='code'><a href="../rasterizerorderedstructuredbuffer-0ahr/index.md" class="code_type">RasterizerOrderedStructuredBuffer</a></span>.



```{toctree}
:titlesonly:
:hidden:

Consume <../types/consumestructuredbuffer-07h/consume-0>
GetDimensions <../types/consumestructuredbuffer-07h/getdimensions-03>
Handle <../types/consumestructuredbuffer-07h/handle-0>
init <../types/consumestructuredbuffer-07h/init>
kind <../types/consumestructuredbuffer-07h/kind>
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
