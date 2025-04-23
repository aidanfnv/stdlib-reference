---
layout: stdlib-reference
---

# struct Atomic\<T\>

## Description

A wrapper for <span class='code'><a href="../../interfaces/iatomicable-01/index.md" class="code_type">IAtomicable</a></span> types to introduce atomic load and store
operations. Values of this type are to be stored in buffers or groupshared
memory.

All operations take a <span class='code'><a href="../memoryorder-06/index.md" class="code_type">MemoryOrder</a></span> parameter which influenced the
semantics of the performed operation

All operations take place at the device scope.

Operators <span class='code'>+=</span>, <span class='code'>-=</span>, <span class='code'>&amp;=</span>, <span class='code'>|=</span>, <span class='code'>^=</span>, <span class='code'>++</span>, <span class='code'>--</span> are overloaded to
operate on <span class='code'><a href="index.md" class="code_type">Atomic</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;</span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T: [IAtomicable](../../interfaces/iatomicable-01/index.md)

## Methods

* [load](load.md)
* [store](store.md)
* [exchange](exchange.md)
* [compareExchange](compareexchange-7.md)
* [add](add.md)
* [sub](sub.md)
* [max](max.md)
* [min](min.md)
* [and](and.md)
* [or](or.md)
* [xor](xor.md)
* [increment](increment.md)
* [decrement](decrement.md)


```{toctree}
:titlesonly:
:hidden:

add <../types/atomic-0/add>
and <../types/atomic-0/and>
compareExchange <../types/atomic-0/compareexchange-7>
decrement <../types/atomic-0/decrement>
exchange <../types/atomic-0/exchange>
increment <../types/atomic-0/increment>
load <../types/atomic-0/load>
max <../types/atomic-0/max>
min <../types/atomic-0/min>
or <../types/atomic-0/or>
store <../types/atomic-0/store>
sub <../types/atomic-0/sub>
xor <../types/atomic-0/xor>
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
