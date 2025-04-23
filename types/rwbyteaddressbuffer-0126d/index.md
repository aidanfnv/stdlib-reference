---
layout: stdlib-reference
---

# struct RWByteAddressBuffer

*Conditionally conforms to:* \_\_IDynamicResourceCastable\<\_\_DynamicResourceKind\.General\>, [IPhysicalBuffer](../../interfaces/iphysicalbuffer-019/index.html), [IRWPhysicalBuffer](../../interfaces/irwphysicalbuffer-0123b/index.html)

## Description

Represents an opaque handle to a read-write buffer allocated in global memory that is indexed in bytes.
This type can be used when working with raw buffers. Raw buffer can be viewed as a bag of bits to
which you want raw access, that is, a buffer that you can conveniently access through chunks of one to
four 32-bit typeless address values.

## Fields

####  <a id="decl-kind"></a>[kind](kind.html) : [DescriptorKind](../descriptorkind-0a/index.html) = [DescriptorKind](../descriptorkind-0a/index.html)\.[Buffer](../descriptorkind-0a/index.html#decl-Buffer)

## Methods

* [GetDimensions](getdimensions-03.html)
* [Load2Aligned](load2aligned-05.html)
* [Load2](load2-0.html)
* [Load3Aligned](load3aligned-05.html)
* [Load3](load3-0.html)
* [Load4Aligned](load4aligned-05.html)
* [Load4](load4-0.html)
* [Load](load-0.html)
* [LoadAligned](loadaligned-04.html)
* [InterlockedAddF64](interlockedaddf64-0be.html)
* [\_NvInterlockedAddFp16x2](0nvinterlockedaddfp16x2-013eh.html)
* [InterlockedAddF16](interlockedaddf16-0be.html)
* [InterlockedAddF16Emulated](interlockedaddf16emulated-0beh.html)
* [InterlockedAddF32](interlockedaddf32-0be.html)
* [InterlockedAddI64](interlockedaddi64-0be.html)
* [InterlockedCompareExchangeU64](interlockedcompareexchangeu64-0biq.html)
* [InterlockedMaxU64](interlockedmaxu64-0be.html)
* [InterlockedMax64](interlockedmax64-0b.html)
* [InterlockedMinU64](interlockedminu64-0be.html)
* [InterlockedMin64](interlockedmin64-0b.html)
* [InterlockedAddU64](interlockedaddu64-0be.html)
* [InterlockedAdd64](interlockedadd64-0b.html)
* [InterlockedAndU64](interlockedandu64-0be.html)
* [InterlockedAnd64](interlockedand64-0b.html)
* [InterlockedOrU64](interlockedoru64-0bd.html)
* [InterlockedOr64](interlockedor64-0b.html)
* [InterlockedXorU64](interlockedxoru64-0be.html)
* [InterlockedXor64](interlockedxor64-0b.html)
* [InterlockedExchangeU64](interlockedexchangeu64-0bj.html)
* [InterlockedExchange64](interlockedexchange64-0b.html)
* [InterlockedCompareExchange64](interlockedcompareexchange64-0bi.html)
* [InterlockedCompareExchangeFloatBitwise](interlockedcompareexchangefloatbitwise-0biqv.html)
* [InterlockedExchangeFloat](interlockedexchangefloat-0bj.html)
* [InterlockedCompareStore64](interlockedcomparestore64-0bi.html)
* [InterlockedCompareStoreFloatBitwise](interlockedcomparestorefloatbitwise-0bins.html)
* [InterlockedMax](interlockedmax-0b.html)
* [InterlockedMin](interlockedmin-0b.html)
* [InterlockedAdd](interlockedadd-0b.html)
* [InterlockedAnd](interlockedand-0b.html)
* [InterlockedOr](interlockedor-0b.html)
* [InterlockedXor](interlockedxor-0b.html)
* [InterlockedExchange](interlockedexchange-0b.html)
* [InterlockedCompareExchange](interlockedcompareexchange-0bi.html)
* [InterlockedCompareStore](interlockedcomparestore-0bi.html)
* [Store2](store2-0.html)
* [Store2Aligned](store2aligned-06.html)
* [Store3](store3-0.html)
* [Store3Aligned](store3aligned-06.html)
* [Store4](store4-0.html)
* [Store4Aligned](store4aligned-06.html)
* [Store](store-0.html)
* [StoreAligned](storealigned-05.html)
* [init](init.html)
* [GetBufferPointer](getbufferpointer-039.html)
* [LoadByteOffset](loadbyteoffset-048.html)
* [StoreByteOffset](storebyteoffset-059.html)

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
