---
layout: stdlib-reference
---

# struct RWByteAddressBuffer

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>, [IPhysicalBuffer](../../interfaces/iphysicalbuffer-019/index.md), [IRWPhysicalBuffer](../../interfaces/irwphysicalbuffer-0123b/index.md)

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
* [InterlockedAddF64](interlockedaddf64-0be.md)
* [\_NvInterlockedAddFp16x2](0nvinterlockedaddfp16x2-013eh.md)
* [InterlockedAddF16](interlockedaddf16-0be.md)
* [InterlockedAddF16Emulated](interlockedaddf16emulated-0beh.md)
* [InterlockedAddF32](interlockedaddf32-0be.md)
* [InterlockedAddI64](interlockedaddi64-0be.md)
* [InterlockedCompareExchangeU64](interlockedcompareexchangeu64-0biq.md)
* [InterlockedMaxU64](interlockedmaxu64-0be.md)
* [InterlockedMax64](interlockedmax64-0b.md)
* [InterlockedMinU64](interlockedminu64-0be.md)
* [InterlockedMin64](interlockedmin64-0b.md)
* [InterlockedAddU64](interlockedaddu64-0be.md)
* [InterlockedAdd64](interlockedadd64-0b.md)
* [InterlockedAndU64](interlockedandu64-0be.md)
* [InterlockedAnd64](interlockedand64-0b.md)
* [InterlockedOrU64](interlockedoru64-0bd.md)
* [InterlockedOr64](interlockedor64-0b.md)
* [InterlockedXorU64](interlockedxoru64-0be.md)
* [InterlockedXor64](interlockedxor64-0b.md)
* [InterlockedExchangeU64](interlockedexchangeu64-0bj.md)
* [InterlockedExchange64](interlockedexchange64-0b.md)
* [InterlockedCompareExchange64](interlockedcompareexchange64-0bi.md)
* [InterlockedCompareExchangeFloatBitwise](interlockedcompareexchangefloatbitwise-0biqv.md)
* [InterlockedExchangeFloat](interlockedexchangefloat-0bj.md)
* [InterlockedCompareStore64](interlockedcomparestore64-0bi.md)
* [InterlockedCompareStoreFloatBitwise](interlockedcomparestorefloatbitwise-0bins.md)
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
* [GetBufferPointer](getbufferpointer-039.md)
* [LoadByteOffset](loadbyteoffset-048.md)
* [StoreByteOffset](storebyteoffset-059.md)

## Conditional Conformances

### Conformance to \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>
`RWByteAddressBuffer` additionally conforms to `\_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>`.
### Conformance to IPhysicalBuffer
`RWByteAddressBuffer` additionally conforms to `IPhysicalBuffer`.
### Conformance to IRWPhysicalBuffer
`RWByteAddressBuffer` additionally conforms to `IRWPhysicalBuffer`.
## Remarks


This type is supported natively when targeting HLSL.



```{toctree}
:titlesonly:
:hidden:

GetBufferPointer <../types/rwbyteaddressbuffer-0126d/getbufferpointer-039>
GetDimensions <../types/rwbyteaddressbuffer-0126d/getdimensions-03>
Handle <../types/rwbyteaddressbuffer-0126d/handle-0>
InterlockedAdd <../types/rwbyteaddressbuffer-0126d/interlockedadd-0b>
InterlockedAdd64 <../types/rwbyteaddressbuffer-0126d/interlockedadd64-0b>
InterlockedAddF16 <../types/rwbyteaddressbuffer-0126d/interlockedaddf16-0be>
InterlockedAddF16Emulated <../types/rwbyteaddressbuffer-0126d/interlockedaddf16emulated-0beh>
InterlockedAddF32 <../types/rwbyteaddressbuffer-0126d/interlockedaddf32-0be>
InterlockedAddF64 <../types/rwbyteaddressbuffer-0126d/interlockedaddf64-0be>
InterlockedAddI64 <../types/rwbyteaddressbuffer-0126d/interlockedaddi64-0be>
InterlockedAddU64 <../types/rwbyteaddressbuffer-0126d/interlockedaddu64-0be>
InterlockedAnd <../types/rwbyteaddressbuffer-0126d/interlockedand-0b>
InterlockedAnd64 <../types/rwbyteaddressbuffer-0126d/interlockedand64-0b>
InterlockedAndU64 <../types/rwbyteaddressbuffer-0126d/interlockedandu64-0be>
InterlockedCompareExchange <../types/rwbyteaddressbuffer-0126d/interlockedcompareexchange-0bi>
InterlockedCompareExchange64 <../types/rwbyteaddressbuffer-0126d/interlockedcompareexchange64-0bi>
InterlockedCompareExchangeFloatBitwise <../types/rwbyteaddressbuffer-0126d/interlockedcompareexchangefloatbitwise-0biqv>
InterlockedCompareExchangeU64 <../types/rwbyteaddressbuffer-0126d/interlockedcompareexchangeu64-0biq>
InterlockedCompareStore <../types/rwbyteaddressbuffer-0126d/interlockedcomparestore-0bi>
InterlockedCompareStore64 <../types/rwbyteaddressbuffer-0126d/interlockedcomparestore64-0bi>
InterlockedCompareStoreFloatBitwise <../types/rwbyteaddressbuffer-0126d/interlockedcomparestorefloatbitwise-0bins>
InterlockedExchange <../types/rwbyteaddressbuffer-0126d/interlockedexchange-0b>
InterlockedExchange64 <../types/rwbyteaddressbuffer-0126d/interlockedexchange64-0b>
InterlockedExchangeFloat <../types/rwbyteaddressbuffer-0126d/interlockedexchangefloat-0bj>
InterlockedExchangeU64 <../types/rwbyteaddressbuffer-0126d/interlockedexchangeu64-0bj>
InterlockedMax <../types/rwbyteaddressbuffer-0126d/interlockedmax-0b>
InterlockedMax64 <../types/rwbyteaddressbuffer-0126d/interlockedmax64-0b>
InterlockedMaxU64 <../types/rwbyteaddressbuffer-0126d/interlockedmaxu64-0be>
InterlockedMin <../types/rwbyteaddressbuffer-0126d/interlockedmin-0b>
InterlockedMin64 <../types/rwbyteaddressbuffer-0126d/interlockedmin64-0b>
InterlockedMinU64 <../types/rwbyteaddressbuffer-0126d/interlockedminu64-0be>
InterlockedOr <../types/rwbyteaddressbuffer-0126d/interlockedor-0b>
InterlockedOr64 <../types/rwbyteaddressbuffer-0126d/interlockedor64-0b>
InterlockedOrU64 <../types/rwbyteaddressbuffer-0126d/interlockedoru64-0bd>
InterlockedXor <../types/rwbyteaddressbuffer-0126d/interlockedxor-0b>
InterlockedXor64 <../types/rwbyteaddressbuffer-0126d/interlockedxor64-0b>
InterlockedXorU64 <../types/rwbyteaddressbuffer-0126d/interlockedxoru64-0be>
Load <../types/rwbyteaddressbuffer-0126d/load-0>
Load2 <../types/rwbyteaddressbuffer-0126d/load2-0>
Load2Aligned <../types/rwbyteaddressbuffer-0126d/load2aligned-05>
Load3 <../types/rwbyteaddressbuffer-0126d/load3-0>
Load3Aligned <../types/rwbyteaddressbuffer-0126d/load3aligned-05>
Load4 <../types/rwbyteaddressbuffer-0126d/load4-0>
Load4Aligned <../types/rwbyteaddressbuffer-0126d/load4aligned-05>
LoadAligned <../types/rwbyteaddressbuffer-0126d/loadaligned-04>
LoadByteOffset <../types/rwbyteaddressbuffer-0126d/loadbyteoffset-048>
Store <../types/rwbyteaddressbuffer-0126d/store-0>
Store2 <../types/rwbyteaddressbuffer-0126d/store2-0>
Store2Aligned <../types/rwbyteaddressbuffer-0126d/store2aligned-06>
Store3 <../types/rwbyteaddressbuffer-0126d/store3-0>
Store3Aligned <../types/rwbyteaddressbuffer-0126d/store3aligned-06>
Store4 <../types/rwbyteaddressbuffer-0126d/store4-0>
Store4Aligned <../types/rwbyteaddressbuffer-0126d/store4aligned-06>
StoreAligned <../types/rwbyteaddressbuffer-0126d/storealigned-05>
StoreByteOffset <../types/rwbyteaddressbuffer-0126d/storebyteoffset-059>
_NvInterlockedAddFp16x2 <../types/rwbyteaddressbuffer-0126d/0nvinterlockedaddfp16x2-013eh>
init <../types/rwbyteaddressbuffer-0126d/init>
kind <../types/rwbyteaddressbuffer-0126d/kind>
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
