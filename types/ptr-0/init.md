---
layout: stdlib-reference
---

# Ptr\<T, addrSpace:uint64\_t\>\.init

## Description





## Signature 

<pre>
<a href="../types/ptr-0/index" class="code_type">Ptr</a>&lt;<a href="init#typeparam-T" class="code_type">T</a>, <a href="init#decl-addrSpace" class="code_var">addrSpace</a>:uint64_t&gt;.<a href="init">init</a>&lt;<a href="init#typeparam-U" class="code_type">U</a>&gt;(Addr&lt;<a href="init#typeparam-U" class="code_type">U</a>&gt; <a href="init#decl-ptr" class="code_param">ptr</a>);

<a href="../types/ptr-0/index" class="code_type">Ptr</a>&lt;<a href="init#typeparam-T" class="code_type">T</a>, <a href="init#decl-addrSpace" class="code_var">addrSpace</a>:uint64_t&gt;.<a href="init">init</a>(uint64_t <a href="init#decl-val" class="code_param">val</a>);

<a href="../types/ptr-0/index" class="code_type">Ptr</a>&lt;<a href="init#typeparam-T" class="code_type">T</a>, <a href="init#decl-addrSpace" class="code_var">addrSpace</a>:uint64_t&gt;.<a href="init">init</a>(int64_t <a href="init#decl-val" class="code_param">val</a>);

Addr&lt;<a href="init#typeparam-T" class="code_type">T</a>&gt;.<a href="init">init</a>(<a href="../types/nativestring-06/index" class="code_type">NativeString</a> <a href="init#decl-nativeStr" class="code_param">nativeStr</a>)
    <span class='code_keyword'>where</span> <a href="init#typeparam-T" class="code_type">T</a> == <span class="code_keyword">void</span>
    <span class='code_keyword'>where</span> <a href="init#decl-addrSpace" class="code_var">addrSpace</a> == 4294967297;

Addr&lt;<a href="init#typeparam-T" class="code_type">T</a>&gt;.<a href="init">init</a>&lt;<a href="init#typeparam-T" class="code_type">T</a>, <a href="init#decl-addrSpace" class="code_var">addrSpace</a>:uint64_t&gt;(Addr&lt;<a href="init#typeparam-T" class="code_type">T</a>&gt; <a href="init#decl-ptr" class="code_param">ptr</a>)
    <span class='code_keyword'>where</span> <a href="init#typeparam-T" class="code_type">T</a> == <span class="code_keyword">void</span>
    <span class='code_keyword'>where</span> <a href="init#decl-addrSpace" class="code_var">addrSpace</a> == 4294967297;

Addr&lt;<a href="init#typeparam-T" class="code_type">T</a>&gt;.<a href="init">init</a>&lt;<a href="init#typeparam-T" class="code_type">T</a>&gt;(NativeRef&lt;<a href="init#typeparam-T" class="code_type">T</a>&gt; <a href="init#decl-ptr" class="code_param">ptr</a>)
    <span class='code_keyword'>where</span> <a href="init#typeparam-T" class="code_type">T</a> == <span class="code_keyword">void</span>
    <span class='code_keyword'>where</span> <a href="init#decl-addrSpace" class="code_var">addrSpace</a> == 4294967297;

</pre>

## Generic Parameters

####  <a id="typeparam-U"></a>U
####  <a id="typeparam-T"></a>T
####  <a id="decl-addrSpace"></a>addrSpace  : uint64\_t

## Parameters

####  <a id="decl-ptr"></a>ptr  : Addr\<[U](init#typeparam-U)\>
####  <a id="decl-val"></a>val  : uint64\_t
####  <a id="decl-val"></a>val  : int64\_t
####  <a id="decl-nativeStr"></a>nativeStr  : [NativeString](../types/nativestring-06/index)
####  <a id="decl-ptr"></a>ptr  : Addr\<[T](init#typeparam-T)\>
####  <a id="decl-ptr"></a>ptr  : NativeRef\<[T](init#typeparam-T)\>

