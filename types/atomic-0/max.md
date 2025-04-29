---
layout: stdlib-reference
---

# Atomic\<T\>\.max

## Description

Atomically computes the maximum of the stored value and the given
value, storing the result and returning the original stored value.




## Signature 

<pre>
<a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a> <a href="../types/atomic-0/index" class="code_type">Atomic</a>&lt;<a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a>&gt;.<a href="max">max</a>(
    <a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a> <a href="max#decl-value" class="code_param">value</a>,
    <a href="../types/memoryorder-06/index" class="code_type">MemoryOrder</a> <a href="max#decl-order" class="code_param">order</a>)
    <span class='code_keyword'>where</span> <a href="../types/atomic-0/index#typeparam-T" class="code_type">T</a> : <a href="../interfaces/iarithmeticatomicable-01b/index" class="code_type">IArithmeticAtomicable</a>;

</pre>

## Parameters

####  <a id="decl-value"></a>value  : [T](../types/atomic-0/index#typeparam-T)
####  <a id="decl-order"></a>order  : [MemoryOrder](../types/memoryorder-06/index) = [MemoryOrder](../types/memoryorder-06/index)\.[Relaxed](../types/memoryorder-06/index#decl-Relaxed)

