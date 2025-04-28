---
layout: stdlib-reference
---

# Atomic\<T\>\.sub

## Description

Atomically subtracts the given value from the stored value and returns
the original stored value.




## Signature 

<pre>
<a href="../types/atomic-0/index.html#typeparam-T" class="code_type">T</a> <a href="../types/atomic-0/index.html" class="code_type">Atomic</a>&lt;<a href="../types/atomic-0/index.html#typeparam-T" class="code_type">T</a>&gt;.<a href="sub.html">sub</a>(
    <a href="../types/atomic-0/index.html#typeparam-T" class="code_type">T</a> <a href="sub.html#decl-value" class="code_param">value</a>,
    <a href="../types/memoryorder-06/index.html" class="code_type">MemoryOrder</a> <a href="sub.html#decl-order" class="code_param">order</a>)
    <span class='code_keyword'>where</span> <a href="../types/atomic-0/index.html#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iarithmeticatomicable-01b/index.html" class="code_type">IArithmeticAtomicable</a>;

</pre>

## Parameters

####  <a id="decl-value"></a>value  : [T](../types/atomic-0/index.html#typeparam-T)
####  <a id="decl-order"></a>order  : [MemoryOrder](../types/memoryorder-06/index.html) = [MemoryOrder](../types/memoryorder-06/index.html)\.[Relaxed](../types/memoryorder-06/index.html#decl-Relaxed)

