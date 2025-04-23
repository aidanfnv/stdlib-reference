---
layout: stdlib-reference
---

# struct CoopMat\<T, S:CoopMatScope, M:int, N:int, R:CoopMatMatrixUse\>

*Conforms to:* [IArray](../../interfaces/iarray-01/index.md)\<[T](../../interfaces/iarray-01/index.md#typeparam-T)\>, [IArithmetic](../../interfaces/iarithmetic-01/index.md)

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-S"></a>S  : [CoopMatScope](../coopmatscope-047/index.md)
####  <a id="decl-M"></a>M  : int
####  <a id="decl-N"></a>N  : int
####  <a id="decl-R"></a>R  : [CoopMatMatrixUse](../coopmatmatrixuse-047d/index.md)

## Methods

* [init](init.md)
* [fill](fill.md)
* [copyFrom](copyfrom-4.md)
* [getCount](getcount-3.md)
* [getRowCount](getrowcount-36.md)
* [getColumnCount](getcolumncount-39.md)
* [subscript](subscript.md)
* [getLength](getlength-3.md)
* [store](store.md)
* [storeAny](storeany-5.md)
* [load](load.md)
* [loadAny](loadany-4.md)
* [add](add.md)
* [sub](sub.md)
* [mul](mul.md)
* [div](div.md)
* [neg](neg.md)
* [mod](mod.md)
* [equals](equals.md)
* [lessThan](lessthan-4.md)
* [lessThanOrEquals](lessthanorequals-48a.md)


```{toctree}
:titlesonly:
:hidden:

add <../types/coopmat-04/add>
copyFrom <../types/coopmat-04/copyfrom-4>
div <../types/coopmat-04/div>
equals <../types/coopmat-04/equals>
fill <../types/coopmat-04/fill>
getColumnCount <../types/coopmat-04/getcolumncount-39>
getCount <../types/coopmat-04/getcount-3>
getLength <../types/coopmat-04/getlength-3>
getRowCount <../types/coopmat-04/getrowcount-36>
init <../types/coopmat-04/init>
lessThan <../types/coopmat-04/lessthan-4>
lessThanOrEquals <../types/coopmat-04/lessthanorequals-48a>
load <../types/coopmat-04/load>
loadAny <../types/coopmat-04/loadany-4>
mod <../types/coopmat-04/mod>
mul <../types/coopmat-04/mul>
neg <../types/coopmat-04/neg>
store <../types/coopmat-04/store>
storeAny <../types/coopmat-04/storeany-5>
sub <../types/coopmat-04/sub>
subscript <../types/coopmat-04/subscript>
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
