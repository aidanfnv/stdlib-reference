---
layout: stdlib-reference
---

# struct RWByteAddressBuffer

## Description

Represents an opaque handle to a read-write buffer allocated in global memory that is indexed in bytes.
This type can be used when working with raw buffers. Raw buffer can be viewed as a bag of bits to
which you want raw access, that is, a buffer that you can conveniently access through chunks of one to
four 32-bit typeless address values.

## Methods

* [GetDimensions](/stdlib-reference/types/rwbyteaddressbuffer-0126d/getdimensions-03)
* [Load2Aligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/load2aligned-05)
* [Load2](/stdlib-reference/types/rwbyteaddressbuffer-0126d/load2-0)
* [Load3Aligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/load3aligned-05)
* [Load3](/stdlib-reference/types/rwbyteaddressbuffer-0126d/load3-0)
* [Load4Aligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/load4aligned-05)
* [Load4](/stdlib-reference/types/rwbyteaddressbuffer-0126d/load4-0)
* [Load](/stdlib-reference/types/rwbyteaddressbuffer-0126d/load-0)
* [LoadAligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/loadaligned-04)
* [InterlockedAddF64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedaddf64-0be)
* [\_NvInterlockedAddFp16x2](/stdlib-reference/types/rwbyteaddressbuffer-0126d/0nvinterlockedaddfp16x2-013eh)
* [InterlockedAddF16](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedaddf16-0be)
* [InterlockedAddF16Emulated](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedaddf16emulated-0beh)
* [InterlockedAddF32](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedaddf32-0be)
* [InterlockedAddI64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedaddi64-0be)
* [InterlockedCompareExchangeU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedcompareexchangeu64-0biq)
* [InterlockedMaxU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedmaxu64-0be)
* [InterlockedMax64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedmax64-0b)
* [InterlockedMinU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedminu64-0be)
* [InterlockedMin64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedmin64-0b)
* [InterlockedAddU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedaddu64-0be)
* [InterlockedAdd64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedadd64-0b)
* [InterlockedAndU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedandu64-0be)
* [InterlockedAnd64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedand64-0b)
* [InterlockedOrU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedoru64-0bd)
* [InterlockedOr64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedor64-0b)
* [InterlockedXorU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedxoru64-0be)
* [InterlockedXor64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedxor64-0b)
* [InterlockedExchangeU64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedexchangeu64-0bj)
* [InterlockedExchange64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedexchange64-0b)
* [InterlockedCompareExchange64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedcompareexchange64-0bi)
* [InterlockedCompareExchangeFloatBitwise](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedcompareexchangefloatbitwise-0biqv)
* [InterlockedExchangeFloat](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedexchangefloat-0bj)
* [InterlockedCompareStore64](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedcomparestore64-0bi)
* [InterlockedCompareStoreFloatBitwise](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedcomparestorefloatbitwise-0bins)
* [InterlockedMax](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedmax-0b)
* [InterlockedMin](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedmin-0b)
* [InterlockedAdd](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedadd-0b)
* [InterlockedAnd](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedand-0b)
* [InterlockedOr](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedor-0b)
* [InterlockedXor](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedxor-0b)
* [InterlockedExchange](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedexchange-0b)
* [InterlockedCompareExchange](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedcompareexchange-0bi)
* [InterlockedCompareStore](/stdlib-reference/types/rwbyteaddressbuffer-0126d/interlockedcomparestore-0bi)
* [Store2](/stdlib-reference/types/rwbyteaddressbuffer-0126d/store2-0)
* [Store2Aligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/store2aligned-06)
* [Store3](/stdlib-reference/types/rwbyteaddressbuffer-0126d/store3-0)
* [Store3Aligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/store3aligned-06)
* [Store4](/stdlib-reference/types/rwbyteaddressbuffer-0126d/store4-0)
* [Store4Aligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/store4aligned-06)
* [Store](/stdlib-reference/types/rwbyteaddressbuffer-0126d/store-0)
* [StoreAligned](/stdlib-reference/types/rwbyteaddressbuffer-0126d/storealigned-05)

## Remarks


This type is supported natively when targeting HLSL.


