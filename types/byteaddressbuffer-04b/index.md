---
layout: stdlib-reference
---

# struct ByteAddressBuffer

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>, [IPhysicalBuffer](../../interfaces/iphysicalbuffer-019/index.md)

## Description

Represents an opaque handle to a read-only buffer allocated in global memory that is indexed in bytes.
ByteAddressBuffer can be used when working with raw buffers. Raw buffer can be viewed as a bag of bits to
which you want raw access, that is, a buffer that you can conveniently access through chunks of one to
four 32-bit typeless address values.

## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) = [DescriptorKind](../descriptorkind-0a/index.md)\.[Buffer](../descriptorkind-0a/index.md#decl-Buffer)

## Methods

* [GetDimensions](getdimensions-03.md)
* [Load2](load2-0.md)
* [Load2Aligned](load2aligned-05.md)
* [Load3](load3-0.md)
* [Load3Aligned](load3aligned-05.md)
* [Load4](load4-0.md)
* [Load4Aligned](load4aligned-05.md)
* [Load](load-0.md)
* [LoadAligned](loadaligned-04.md)
* [init](init.md)
* [GetBufferPointer](getbufferpointer-039.md)
* [LoadByteOffset](loadbyteoffset-048.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`ByteAddressBuffer` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>`.
### Conformance to IPhysicalBuffer
`ByteAddressBuffer` additionally conforms to `IPhysicalBuffer`.
## Remarks


This type is supported natively when targeting HLSL.
For all other targets, this type maps to a buffer of 32bit unsigned integers.



```{toctree}
:titlesonly:
:hidden:

GetBufferPointer <../types/byteaddressbuffer-04b/getbufferpointer-039>
GetDimensions <../types/byteaddressbuffer-04b/getdimensions-03>
Handle <../types/byteaddressbuffer-04b/handle-0>
Load <../types/byteaddressbuffer-04b/load-0>
Load2 <../types/byteaddressbuffer-04b/load2-0>
Load2Aligned <../types/byteaddressbuffer-04b/load2aligned-05>
Load3 <../types/byteaddressbuffer-04b/load3-0>
Load3Aligned <../types/byteaddressbuffer-04b/load3aligned-05>
Load4 <../types/byteaddressbuffer-04b/load4-0>
Load4Aligned <../types/byteaddressbuffer-04b/load4aligned-05>
LoadAligned <../types/byteaddressbuffer-04b/loadaligned-04>
LoadByteOffset <../types/byteaddressbuffer-04b/loadbyteoffset-048>
init <../types/byteaddressbuffer-04b/init>
kind <../types/byteaddressbuffer-04b/kind>
```

<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
