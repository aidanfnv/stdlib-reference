---
layout: stdlib-reference
---

# TensorView\<T\>\.load

## Description





## Signature 

<pre>
<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a> <a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a>&gt;.<a href="load">load</a>(<span class="code_keyword">uint</span> <a href="load#decl-x" class="code_param">x</a>);

<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a> <a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a>&gt;.<a href="load">load</a>(
    <span class="code_keyword">uint</span> <a href="load#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-y" class="code_param">y</a>);

<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a> <a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a>&gt;.<a href="load">load</a>(
    <span class="code_keyword">uint</span> <a href="load#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-y" class="code_param">y</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-z" class="code_param">z</a>);

<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a> <a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a>&gt;.<a href="load">load</a>(
    <span class="code_keyword">uint</span> <a href="load#decl-x" class="code_param">x</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-y" class="code_param">y</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-z" class="code_param">z</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-w" class="code_param">w</a>);

<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a> <a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a>&gt;.<a href="load">load</a>(
    <span class="code_keyword">uint</span> <a href="load#decl-i0" class="code_param">i0</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-i1" class="code_param">i1</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-i2" class="code_param">i2</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-i3" class="code_param">i3</a>,
    <span class="code_keyword">uint</span> <a href="load#decl-i4" class="code_param">i4</a>);

<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a> <a href="../types/tensorview-06/index" class="code_type">TensorView</a>&lt;<a href="../types/tensorview-06/index#typeparam-T" class="code_type">T</a>&gt;.<a href="load">load</a>&lt;<a href="load#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(<a href="../types/vector/index" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="load#decl-N" class="code_var">N</a>&gt; <a href="load#decl-index" class="code_param">index</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-x"></a>x  : uint
####  <a id="decl-y"></a>y  : uint
####  <a id="decl-z"></a>z  : uint
####  <a id="decl-w"></a>w  : uint
####  <a id="decl-i0"></a>i0  : uint
####  <a id="decl-i1"></a>i1  : uint
####  <a id="decl-i2"></a>i2  : uint
####  <a id="decl-i3"></a>i3  : uint
####  <a id="decl-i4"></a>i4  : uint
####  <a id="decl-index"></a>index  : [vector](../types/vector/index)\<uint, [N](../types/vector/index#decl-N)\>

## Availability and Requirements

Defined for the following targets:

#### cuda
Available in all stages.



