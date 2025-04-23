---
layout: stdlib-reference
---

# struct CoopVec\<T, N:int\>

*Conforms to:* [IArray](../../interfaces/iarray-01/index.html)\<[T](../../interfaces/iarray-01/index.html#typeparam-T)\>, [IArithmetic](../../interfaces/iarithmetic-01/index.html)

## Description

Represents a Cooperative Vector type that is for matrix-vector multiplication that
can take an advantage of the hardware acceleration. It can be used for evaluations
of neural network in graphics and compute pipeline.

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.html)
The element type of the CoopVec.

####  <a id="decl-N"></a>N  : int
The vector size.


## Methods

* [init](init.html)
* [copyFrom](copyfrom-4.html)
* [fill](fill.html)
* [store](store.html)
* [storeAny](storeany-5.html)
* [load](load.html)
* [loadAny](loadany-4.html)
* [getCount](getcount-3.html)
* [subscript](subscript.html)
* [replicate](replicate.html)
* [equals](equals.html)
* [lessThan](lessthan-4.html)
* [lessThanOrEquals](lessthanorequals-48a.html)
* [add](add.html)
* [sub](sub.html)
* [mul](mul.html)
* [div](div.html)
* [mod](mod.html)
* [neg](neg.html)
* [matMulAccumPacked](matmulaccumpacked-36b.html)
* [matMulAccum](matmulaccum-36.html)
* [matMulAddAccumPacked](matmuladdaccumpacked-369e.html)
* [matMulAddAccum](matmuladdaccum-369.html)


```{toctree}
:titlesonly:
:hidden:

add <../types/coopvec-04/add>
copyFrom <../types/coopvec-04/copyfrom-4>
div <../types/coopvec-04/div>
equals <../types/coopvec-04/equals>
fill <../types/coopvec-04/fill>
getCount <../types/coopvec-04/getcount-3>
init <../types/coopvec-04/init>
lessThan <../types/coopvec-04/lessthan-4>
lessThanOrEquals <../types/coopvec-04/lessthanorequals-48a>
load <../types/coopvec-04/load>
loadAny <../types/coopvec-04/loadany-4>
matMulAccum <../types/coopvec-04/matmulaccum-36>
matMulAccumPacked <../types/coopvec-04/matmulaccumpacked-36b>
matMulAddAccum <../types/coopvec-04/matmuladdaccum-369>
matMulAddAccumPacked <../types/coopvec-04/matmuladdaccumpacked-369e>
mod <../types/coopvec-04/mod>
mul <../types/coopvec-04/mul>
neg <../types/coopvec-04/neg>
replicate <../types/coopvec-04/replicate>
store <../types/coopvec-04/store>
storeAny <../types/coopvec-04/storeany-5>
sub <../types/coopvec-04/sub>
subscript <../types/coopvec-04/subscript>
```
