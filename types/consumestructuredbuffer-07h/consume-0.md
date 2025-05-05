---
layout: stdlib-reference
---

# ConsumeStructuredBuffer\<T, L\>\.Consume

## Description

Reading the element at the end of the buffer indicated by the associated atomic counter
and decrement the builtin atomic counter by 1.



## Signature 

<pre>
<a href="/stdlib-reference/types/consumestructuredbuffer-07h/index#typeparam-T" class="code_type">T</a> <a href="/stdlib-reference/types/consumestructuredbuffer-07h/index" class="code_type">ConsumeStructuredBuffer</a>&lt;<a href="/stdlib-reference/types/consumestructuredbuffer-07h/index#typeparam-T" class="code_type">T</a>, <a href="/stdlib-reference/types/consumestructuredbuffer-07h/index#typeparam-L" class="code_type">L</a>&gt;.<a href="/stdlib-reference/types/consumestructuredbuffer-07h/consume-0">Consume</a>()
    <span class='code_keyword'>where</span> <a href="/stdlib-reference/types/consumestructuredbuffer-07h/index#typeparam-L" class="code_type">L</a> : <a href="/stdlib-reference/interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

</pre>

## Return value
The element read from the buffer, it can be a structure.


