---
layout: stdlib-reference
---

# Atomic\<T\>\.decrement

## Description

Atomically decrements the stored value and returns the original stored
value.




## Signature 

<pre>
<a href="index.html#typeparam-T" class="code_type">T</a> <a href="index.html" class="code_type">Atomic</a>&lt;<a href="index.html#typeparam-T" class="code_type">T</a>&gt;.<a href="decrement.html">decrement</a>(<a href="index.html" class="code_type">MemoryOrder</a> <a href="decrement.html#decl-order" class="code_param">order</a>)
    <span class='code_keyword'>where</span> <a href="index.html#typeparam-T" class="code_type">T</a> : <a href="index.html" class="code_type">IBitAtomicable</a>;

</pre>

## Parameters

####  <a id="decl-order"></a>order  : [MemoryOrder](../memoryorder-06/index) = [MemoryOrder](../memoryorder-06/index)\.[Relaxed](../memoryorder-06/index#decl-Relaxed)

