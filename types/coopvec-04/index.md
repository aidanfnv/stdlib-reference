---
layout: stdlib-reference
---

# struct CoopVec\<T, N:int\>

*Conforms to:* [IArray](../../interfaces/iarray-01/index.md)\<[T](../../interfaces/iarray-01/index.md#typeparam-T)\>, [IArithmetic](../../interfaces/iarithmetic-01/index.md)

## Description

Represents a Cooperative Vector type that is for matrix-vector multiplication that
can take an advantage of the hardware acceleration. It can be used for evaluations
of neural network in graphics and compute pipeline.

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.md)
The element type of the CoopVec.

####  <a id="decl-N"></a>N  : int
The vector size.


## Methods

* [init](init.md)
* [copyFrom](copyfrom-4.md)
* [fill](fill.md)
* [store](store.md)
* [storeAny](storeany-5.md)
* [load](load.md)
* [loadAny](loadany-4.md)
* [getCount](getcount-3.md)
* [subscript](subscript.md)
* [replicate](replicate.md)
* [equals](equals.md)
* [lessThan](lessthan-4.md)
* [lessThanOrEquals](lessthanorequals-48a.md)
* [add](add.md)
* [sub](sub.md)
* [mul](mul.md)
* [div](div.md)
* [mod](mod.md)
* [neg](neg.md)
* [matMulAccumPacked](matmulaccumpacked-36b.md)
* [matMulAccum](matmulaccum-36.md)
* [matMulAddAccumPacked](matmuladdaccumpacked-369e.md)
* [matMulAddAccum](matmuladdaccum-369.md)


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
