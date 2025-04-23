---
layout: stdlib-reference
---

# struct RasterizerOrderedByteAddressBuffer

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>

## Description

Represents an opaque handle to a read-write buffer allocated in global memory that is indexed in bytes.
This type can be used when working with raw buffers. Raw buffer can be viewed as a bag of bits to
which you want raw access, that is, a buffer that you can conveniently access through chunks of one to
four 32-bit typeless address values.

## Fields

####  <a id="decl-kind"></a>[kind](kind.md) : [DescriptorKind](../descriptorkind-0a/index.md) = [DescriptorKind](../descriptorkind-0a/index.md)\.[Buffer](../descriptorkind-0a/index.md#decl-Buffer)

## Methods

* [GetDimensions](getdimensions-03.md)
* [Load2Aligned](load2aligned-05.md)
* [Load2](load2-0.md)
* [Load3Aligned](load3aligned-05.md)
* [Load3](load3-0.md)
* [Load4Aligned](load4aligned-05.md)
* [Load4](load4-0.md)
* [Load](load-0.md)
* [LoadAligned](loadaligned-04.md)
* [InterlockedMax](interlockedmax-0b.md)
* [InterlockedMin](interlockedmin-0b.md)
* [InterlockedAdd](interlockedadd-0b.md)
* [InterlockedAnd](interlockedand-0b.md)
* [InterlockedOr](interlockedor-0b.md)
* [InterlockedXor](interlockedxor-0b.md)
* [InterlockedExchange](interlockedexchange-0b.md)
* [InterlockedCompareExchange](interlockedcompareexchange-0bi.md)
* [InterlockedCompareStore](interlockedcomparestore-0bi.md)
* [Store2](store2-0.md)
* [Store2Aligned](store2aligned-06.md)
* [Store3](store3-0.md)
* [Store3Aligned](store3aligned-06.md)
* [Store4](store4-0.md)
* [Store4Aligned](store4aligned-06.md)
* [Store](store-0.md)
* [StoreAligned](storealigned-05.md)
* [init](init.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`RasterizerOrderedByteAddressBuffer` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>`.
## Remarks


This type is supported natively when targeting HLSL.



```{toctree}
:titlesonly:
:hidden:

GetDimensions <../types/rasterizerorderedbyteaddressbuffer-0ahls/getdimensions-03>
Handle <../types/rasterizerorderedbyteaddressbuffer-0ahls/handle-0>
InterlockedAdd <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedadd-0b>
InterlockedAnd <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedand-0b>
InterlockedCompareExchange <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedcompareexchange-0bi>
InterlockedCompareStore <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedcomparestore-0bi>
InterlockedExchange <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedexchange-0b>
InterlockedMax <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedmax-0b>
InterlockedMin <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedmin-0b>
InterlockedOr <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedor-0b>
InterlockedXor <../types/rasterizerorderedbyteaddressbuffer-0ahls/interlockedxor-0b>
Load <../types/rasterizerorderedbyteaddressbuffer-0ahls/load-0>
Load2 <../types/rasterizerorderedbyteaddressbuffer-0ahls/load2-0>
Load2Aligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/load2aligned-05>
Load3 <../types/rasterizerorderedbyteaddressbuffer-0ahls/load3-0>
Load3Aligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/load3aligned-05>
Load4 <../types/rasterizerorderedbyteaddressbuffer-0ahls/load4-0>
Load4Aligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/load4aligned-05>
LoadAligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/loadaligned-04>
Store <../types/rasterizerorderedbyteaddressbuffer-0ahls/store-0>
Store2 <../types/rasterizerorderedbyteaddressbuffer-0ahls/store2-0>
Store2Aligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/store2aligned-06>
Store3 <../types/rasterizerorderedbyteaddressbuffer-0ahls/store3-0>
Store3Aligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/store3aligned-06>
Store4 <../types/rasterizerorderedbyteaddressbuffer-0ahls/store4-0>
Store4Aligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/store4aligned-06>
StoreAligned <../types/rasterizerorderedbyteaddressbuffer-0ahls/storealigned-05>
init <../types/rasterizerorderedbyteaddressbuffer-0ahls/init>
kind <../types/rasterizerorderedbyteaddressbuffer-0ahls/kind>
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
