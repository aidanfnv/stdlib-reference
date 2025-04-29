---
layout: stdlib-reference
---

# StructuredBuffer\<T, L\>\.init

## Description





## Signature 

<pre>
<a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a>&lt;<a href="../types/structuredbuffer-0a/index#typeparam-T" class="code_type">T</a>, <a href="../types/structuredbuffer-0a/index#typeparam-L" class="code_type">L</a>&gt;.<a href="init">init</a>(__DynamicResource&lt;__DynamicResourceKind.General&gt; <a href="init#decl-res" class="code_param">res</a>)
    <span class='code_keyword'>where</span> <a href="../types/structuredbuffer-0a/index#typeparam-L" class="code_type">L</a> : <a href="../interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

<a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a>&lt;<a href="../types/structuredbuffer-0a/index#typeparam-T" class="code_type">T</a>, <a href="../types/structuredbuffer-0a/index#typeparam-L" class="code_type">L</a>&gt;.<a href="init">init</a>(<a href="../types/descriptorhandle-0a/index" class="code_type">DescriptorHandle</a>&lt;<a href="../types/structuredbuffer-0a/index" class="code_type">StructuredBuffer</a>&lt;<a href="../types/structuredbuffer-0a/index#typeparam-T" class="code_type">T</a>, <a href="../types/structuredbuffer-0a/index#typeparam-L" class="code_type">L</a>&gt;&gt; <a href="init#decl-bindless" class="code_param">bindless</a>)
    <span class='code_keyword'>where</span> <a href="../types/structuredbuffer-0a/index#typeparam-L" class="code_type">L</a> : <a href="../interfaces/ibufferdatalayout-017b/index" class="code_type">IBufferDataLayout</a>;

</pre>

## Parameters

####  <a id="decl-res"></a>res  : \_\_DynamicResource\<\_\_DynamicResourceKind\.General\>
####  <a id="decl-bindless"></a>bindless  : [DescriptorHandle](../types/descriptorhandle-0a/index)\<[StructuredBuffer](../types/structuredbuffer-0a/index)\<[T](../types/structuredbuffer-0a/index#typeparam-T), [L](../types/structuredbuffer-0a/index#typeparam-L) \>\>

