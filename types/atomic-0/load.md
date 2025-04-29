---
layout: stdlib-reference
---

# Atomic\<T\>\.load

## Description

Atomically load the stored <span class='code'><a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a></span> value




## Signature 

<pre>
<a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a> <a href="../types/atomic-0/index" class="code_type">Atomic</a>&lt;<a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a>&gt;.<a href="load">load</a>(<a href="../types/memoryorder-06/index" class="code_type">MemoryOrder</a> <a href="load#decl-order" class="code_param">order</a>)
    <span class='code_keyword'>where</span> <a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iatomicable-01/index" class="code_type">IAtomicable</a>;

</pre>

## Parameters

####  <a id="decl-order"></a>order  : [MemoryOrder](../types/memoryorder-06/index) = [MemoryOrder](../types/memoryorder-06/index)\.[Relaxed](../types/memoryorder-06/index#decl-Relaxed)

