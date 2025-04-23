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
