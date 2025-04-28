---
layout: stdlib-reference
---

# struct CoopVec\<T, N:int\>

*Conforms to:* [IArray](../interfaces/iarray-01/index.html)\<[T](../interfaces/iarray-01/index.html#typeparam-T)\>, [IArithmetic](../interfaces/iarithmetic-01/index.html)

## Description

Represents a Cooperative Vector type that is for matrix-vector multiplication that
can take an advantage of the hardware acceleration. It can be used for evaluations
of neural network in graphics and compute pipeline.

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.html)
The element type of the CoopVec.

####  <a id="decl-N"></a>N  : int
The vector size.


## Methods

* [init](../init.html)
* [copyFrom](../copyfrom-4.html)
* [fill](../fill.html)
* [store](../store.html)
* [storeAny](../storeany-5.html)
* [load](../load.html)
* [loadAny](../loadany-4.html)
* [getCount](../getcount-3.html)
* [subscript](../subscript.html)
* [replicate](../replicate.html)
* [equals](../equals.html)
* [lessThan](../lessthan-4.html)
* [lessThanOrEquals](../lessthanorequals-48a.html)
* [add](../add.html)
* [sub](../sub.html)
* [mul](../mul.html)
* [div](../div.html)
* [mod](../mod.html)
* [neg](../neg.html)
* [matMulAccumPacked](../matmulaccumpacked-36b.html)
* [matMulAccum](../matmulaccum-36.html)
* [matMulAddAccumPacked](../matmuladdaccumpacked-369e.html)
* [matMulAddAccum](../matmuladdaccum-369.html)


```{toctree}
:titlesonly:
:hidden:

add <add>
copyFrom <copyfrom-4>
div <div>
equals <equals>
fill <fill>
getCount <getcount-3>
init <init>
lessThan <lessthan-4>
lessThanOrEquals <lessthanorequals-48a>
load <load>
loadAny <loadany-4>
matMulAccum <matmulaccum-36>
matMulAccumPacked <matmulaccumpacked-36b>
matMulAddAccum <matmuladdaccum-369>
matMulAddAccumPacked <matmuladdaccumpacked-369e>
mod <mod>
mul <mul>
neg <neg>
replicate <replicate>
store <store>
storeAny <storeany-5>
sub <sub>
subscript <subscript>
```
