---
layout: stdlib-reference
---

# Atomic\<T\>\.exchange

## Description

Atomically replace the stored <span class='code'><a href="/stdlib-reference/types/atomic-0/index#typeparam-T" class="code_type">T</a></span> value with a new <span class='code'><a href="/stdlib-reference/types/atomic-0/index#typeparam-T" class="code_type">T</a></span> value and return
replaced value




## Signature 

<pre>
<a href="/stdlib-reference/types/atomic-0/index#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/types/atomic-0/index" class="code_type">Atomic</a>&lt;<a href="/stdlib-reference/types/atomic-0/index#typeparam-T" class="code_type">T</a>&gt;.<a href="/stdlib-reference/types/atomic-0/exchange">exchange</a>(
    <a href="/stdlib-reference/types/atomic-0/index#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/types/atomic-0/exchange#decl-newValue" class="code_param">newValue</a>,
    <a href="/stdlib-reference/types/memoryorder-06/index" class="code_type">MemoryOrder</a> <a href="/stdlib-reference/types/atomic-0/exchange#decl-order" class="code_param">order</a>)
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/atomic-0/index#typeparam-T" class="code_type">T</a> : <a href="/stdlib-reference/interfaces/iatomicable-01/index" class="code_type">IAtomicable</a>;

</pre>

## Parameters

#### newValue  : [T](/stdlib-reference/types/atomic-0/index#typeparam-T) {#decl-newValue}
#### order  : [MemoryOrder](/stdlib-reference/types/memoryorder-06/index) = [MemoryOrder](/stdlib-reference/types/memoryorder-06/index)\.[Relaxed](/stdlib-reference/types/memoryorder-06/index#decl-Relaxed) {#decl-order}

