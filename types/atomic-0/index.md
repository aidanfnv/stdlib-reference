---
layout: stdlib-reference
---

# struct Atomic\<T\>

## Description

A wrapper for <span class='code'><a href="../../interfaces/iatomicable-01/index.html" class="code_type">IAtomicable</a></span> types to introduce atomic load and store
operations. Values of this type are to be stored in buffers or groupshared
memory.

All operations take a <span class='code'><a href="../memoryorder-06/index.html" class="code_type">MemoryOrder</a></span> parameter which influenced the
semantics of the performed operation

All operations take place at the device scope.

Operators <span class='code'>+=</span>, <span class='code'>-=</span>, <span class='code'>&amp;=</span>, <span class='code'>|=</span>, <span class='code'>^=</span>, <span class='code'>++</span>, <span class='code'>--</span> are overloaded to
operate on <span class='code'><a href="index.html" class="code_type">Atomic</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>&gt;</span>.


## Generic Parameters

####  <a id="typeparam-T"></a>T: [IAtomicable](../../interfaces/iatomicable-01/index.html)

## Methods

* [load](load.html)
* [store](store.html)
* [exchange](exchange.html)
* [compareExchange](compareexchange-7.html)
* [add](add.html)
* [sub](sub.html)
* [max](max.html)
* [min](min.html)
* [and](and.html)
* [or](or.html)
* [xor](xor.html)
* [increment](increment.html)
* [decrement](decrement.html)


```{toctree}
:titlesonly:
:hidden:

add <add>
and <and>
compareExchange <compareexchange-7>
decrement <decrement>
exchange <exchange>
increment <increment>
load <load>
max <max>
min <min>
or <or>
store <store>
sub <sub>
xor <xor>
```
