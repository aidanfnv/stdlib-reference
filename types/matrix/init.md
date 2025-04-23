---
layout: stdlib-reference
---

# matrix\<T, R:int, C:int, L:int\>\.init

## Description

Initialize a vector from a value of the same type




## Signature 

<pre>
<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="index.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>, <a href="index.md#decl-L" class="code_var">L</a>:<span class="code_keyword">int</span>&gt;.<a href="init.md">init</a>(<a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-val" class="code_param">val</a>);

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="index.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>, <a href="index.md#decl-L" class="code_var">L</a>:<span class="code_keyword">int</span>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt; <a href="init.md#decl-value" class="code_param">value</a>);

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<span class="code_keyword">int</span> <a href="init.md#decl-v" class="code_param">v</a>)
    <span class='code_keyword'>where</span> <a href="t-0.md" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<span class="code_keyword">float</span> <a href="init.md#decl-v" class="code_param">v</a>)
    <span class='code_keyword'>where</span> <a href="t-0.md" class="code_type">T</a> : <a href="../../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<span class="code_keyword">int</span> <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="t-0.md" class="code_type">T</a> == int16_t;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row0" class="code_param">row0</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 1&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 1&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 1&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row0" class="code_param">row0</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row0" class="code_param">row0</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m03" class="code_param">m03</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row0" class="code_param">row0</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 1
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row1" class="code_param">row1</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 1&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 1&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row1" class="code_param">row1</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m12" class="code_param">m12</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row1" class="code_param">row1</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m03" class="code_param">m03</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m12" class="code_param">m12</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m13" class="code_param">m13</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row1" class="code_param">row1</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 2
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 1&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 1&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m21" class="code_param">m21</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 2&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m12" class="code_param">m12</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m21" class="code_param">m21</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m22" class="code_param">m22</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 3&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m03" class="code_param">m03</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m12" class="code_param">m12</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m13" class="code_param">m13</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m21" class="code_param">m21</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m22" class="code_param">m22</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m23" class="code_param">m23</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2, 4&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row2" class="code_param">row2</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 3
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m30" class="code_param">m30</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row2" class="code_param">row2</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 2&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 1&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 1&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 1;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m21" class="code_param">m21</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m30" class="code_param">m30</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m31" class="code_param">m31</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row2" class="code_param">row2</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 3&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 2&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 2&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 2;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m12" class="code_param">m12</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m21" class="code_param">m21</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m22" class="code_param">m22</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m30" class="code_param">m30</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m31" class="code_param">m31</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m32" class="code_param">m32</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row2" class="code_param">row2</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4, 4&gt; <a href="init.md#decl-value" class="code_param">value</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 3&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 3;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m00" class="code_param">m00</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m01" class="code_param">m01</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m02" class="code_param">m02</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m03" class="code_param">m03</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m10" class="code_param">m10</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m11" class="code_param">m11</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m12" class="code_param">m12</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m13" class="code_param">m13</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m20" class="code_param">m20</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m21" class="code_param">m21</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m22" class="code_param">m22</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m23" class="code_param">m23</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m30" class="code_param">m30</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m31" class="code_param">m31</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m32" class="code_param">m32</a>,
    <a href="t-0.md" class="code_type">T</a> <a href="init.md#decl-m33" class="code_param">m33</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row0" class="code_param">row0</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row1" class="code_param">row1</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row2" class="code_param">row2</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

<a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, <a href="index.md#decl-R" class="code_var">R</a>, <a href="index.md#decl-C" class="code_var">C</a>&gt;.<a href="init.md">init</a>(
    <a href="index.md" class="code_type">matrix</a>&lt;<a href="t-0.md" class="code_type">T</a>, 3, 4&gt; <a href="init.md#decl-m" class="code_param">m</a>,
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<a href="t-0.md" class="code_type">T</a>, 4&gt; <a href="init.md#decl-row3" class="code_param">row3</a>)
    <span class='code_keyword'>where</span> <a href="index.md#decl-R" class="code_var">R</a> == 4
    <span class='code_keyword'>where</span> <a href="index.md#decl-C" class="code_var">C</a> == 4;

</pre>

## Parameters

####  <a id="decl-val"></a>val  : [T](t-0.md)
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), [R](index.md#decl-R), [C](index.md#decl-C)\>
####  <a id="decl-v"></a>v  : int
####  <a id="decl-v"></a>v  : float
####  <a id="decl-value"></a>value  : int
####  <a id="decl-value"></a>value  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 4\>
####  <a id="decl-m00"></a>m00  : [T](t-0.md)
####  <a id="decl-row0"></a>row0  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 1\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 1, 2\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 1, 3\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 1, 4\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 2, 1\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 2, 2\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 2, 3\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 2, 4\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 3, 1\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 3, 2\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 3, 3\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 3, 4\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 4, 1\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 4, 2\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 4, 3\>
####  <a id="decl-value"></a>value  : [matrix](index.md)\<[T](t-0.md), 4, 4\>
####  <a id="decl-m01"></a>m01  : [T](t-0.md)
####  <a id="decl-row0"></a>row0  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 2\>
####  <a id="decl-m02"></a>m02  : [T](t-0.md)
####  <a id="decl-row0"></a>row0  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 3\>
####  <a id="decl-m03"></a>m03  : [T](t-0.md)
####  <a id="decl-row0"></a>row0  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 4\>
####  <a id="decl-m10"></a>m10  : [T](t-0.md)
####  <a id="decl-row1"></a>row1  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 1\>
####  <a id="decl-m11"></a>m11  : [T](t-0.md)
####  <a id="decl-row1"></a>row1  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 2\>
####  <a id="decl-m12"></a>m12  : [T](t-0.md)
####  <a id="decl-row1"></a>row1  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 3\>
####  <a id="decl-m13"></a>m13  : [T](t-0.md)
####  <a id="decl-row1"></a>row1  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 4\>
####  <a id="decl-m20"></a>m20  : [T](t-0.md)
####  <a id="decl-row2"></a>row2  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 1\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 2, 1\>
####  <a id="decl-m21"></a>m21  : [T](t-0.md)
####  <a id="decl-row2"></a>row2  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 2\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 2, 2\>
####  <a id="decl-m22"></a>m22  : [T](t-0.md)
####  <a id="decl-row2"></a>row2  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 3\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 2, 3\>
####  <a id="decl-m23"></a>m23  : [T](t-0.md)
####  <a id="decl-row2"></a>row2  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 4\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 2, 4\>
####  <a id="decl-m30"></a>m30  : [T](t-0.md)
####  <a id="decl-row3"></a>row3  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 1\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 3, 1\>
####  <a id="decl-m31"></a>m31  : [T](t-0.md)
####  <a id="decl-row3"></a>row3  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 2\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 3, 2\>
####  <a id="decl-m32"></a>m32  : [T](t-0.md)
####  <a id="decl-row3"></a>row3  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 3\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 3, 3\>
####  <a id="decl-m33"></a>m33  : [T](t-0.md)
####  <a id="decl-row3"></a>row3  : [vector](../vector/index.md)\<[T](../vector/index.md#typeparam-T), 4\>
####  <a id="decl-m"></a>m  : [matrix](index.md)\<[T](t-0.md), 3, 4\>

## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.




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
