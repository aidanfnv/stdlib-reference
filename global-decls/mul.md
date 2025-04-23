---
layout: stdlib-reference
---

# mul

## Description

Multiply.



## Signature 

<pre>
<a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>&gt;(
    <a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md#decl-x" class="code_param">x</a>,
    <a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-x" class="code_param">x</a>,
    <a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-x" class="code_param">x</a>,
    <a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md#decl-x" class="code_param">x</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinarithmetictype-029j/index.md" class="code_type">__BuiltinArithmeticType</a>;

<a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="mul.md#typeparam-T" class="code_type">T</a> <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-x" class="code_param">x</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-y" class="code_param">y</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinlogicaltype-029g/index.md" class="code_type">__BuiltinLogicalType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinlogicaltype-029g/index.md" class="code_type">__BuiltinLogicalType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinintegertype-029g/index.md" class="code_type">__BuiltinIntegerType</a>;

<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinlogicaltype-029g/index.md" class="code_type">__BuiltinLogicalType</a>;

<a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt;&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt;&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt;&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt;&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-M" class="code_var">M</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt;&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/vector/index.md" class="code_type">vector</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-M" class="code_var">M</a>&gt;&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt;&gt; <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt;&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt;&gt; <a href="mul.md#decl-right" class="code_param">right</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

<span class="code_keyword">void</span> <a href="mul.md">mul</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>, <a href="mul.md#decl-C" class="code_var">C</a>:<span class="code_keyword">int</span>&gt;(
    <span class="code_keyword">inout</span> <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-N" class="code_var">N</a>&gt;&gt; <a href="mul.md#decl-left" class="code_param">left</a>,
    <span class="code_keyword">inout</span> <a href="../types/differentialpair-0c/index.md" class="code_type">DifferentialPair</a>&lt;<a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-N" class="code_var">N</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt;&gt; <a href="mul.md#decl-right" class="code_param">right</a>,
    <a href="../types/matrix/index.md" class="code_type">matrix</a>&lt;<a href="mul.md#typeparam-T" class="code_type">T</a>, <a href="mul.md#decl-R" class="code_var">R</a>, <a href="mul.md#decl-C" class="code_var">C</a>&gt; <a href="mul.md#decl-dOut" class="code_param">dOut</a>)
    <span class='code_keyword'>where</span> <a href="mul.md#typeparam-T" class="code_type">T</a> : <a href="../interfaces/0_builtinfloatingpointtype-029hm/index.md" class="code_type">__BuiltinFloatingPointType</a>;

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T: [\_\_BuiltinArithmeticType](../interfaces/0_builtinarithmetictype-029j/index.md)
####  <a id="decl-N"></a>N  : int
####  <a id="decl-M"></a>M  : int
####  <a id="typeparam-T"></a>T: [\_\_BuiltinFloatingPointType](../interfaces/0_builtinfloatingpointtype-029hm/index.md)
####  <a id="typeparam-T"></a>T: [\_\_BuiltinIntegerType](../interfaces/0_builtinintegertype-029g/index.md)
####  <a id="typeparam-T"></a>T: [\_\_BuiltinLogicalType](../interfaces/0_builtinlogicaltype-029g/index.md)
####  <a id="decl-R"></a>R  : int
####  <a id="decl-C"></a>C  : int

## Parameters

####  <a id="decl-x"></a>x  : [T](mul.md#typeparam-T)
The first value.

####  <a id="decl-y"></a>y  : [T](mul.md#typeparam-T)
The second value.

####  <a id="decl-x"></a>x  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The first value.

####  <a id="decl-y"></a>y  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
The second value.

####  <a id="decl-x"></a>x  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The first value.

####  <a id="decl-y"></a>y  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
The second value.

####  <a id="decl-left"></a>left  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N)\>
####  <a id="decl-right"></a>right  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
####  <a id="decl-left"></a>left  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M)\>
####  <a id="decl-right"></a>right  : [vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), M\>
####  <a id="decl-left"></a>left  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [R](../types/matrix/index.md#decl-R), [N](../types/matrix/index.md#decl-N)\>
####  <a id="decl-right"></a>right  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [C](../types/matrix/index.md#decl-C)\>
####  <a id="decl-left"></a>left  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), [N](../types/vector/index.md#decl-N) \>\>
####  <a id="decl-right"></a>right  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M) \>\>
####  <a id="decl-left"></a>left  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [M](../types/matrix/index.md#decl-M) \>\>
####  <a id="decl-right"></a>right  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[vector](../types/vector/index.md)\<[T](../types/vector/index.md#typeparam-T), M \>\>
####  <a id="decl-left"></a>left  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [R](../types/matrix/index.md#decl-R), [N](../types/matrix/index.md#decl-N) \>\>
####  <a id="decl-right"></a>right  : [DifferentialPair](../types/differentialpair-0c/index.md)\<[matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [N](../types/matrix/index.md#decl-N), [C](../types/matrix/index.md#decl-C) \>\>
####  <a id="decl-dOut"></a>dOut  : [matrix](../types/matrix/index.md)\<[T](../types/matrix/t-0.md), [R](../types/matrix/index.md#decl-R), [C](../types/matrix/index.md#decl-C)\>

## Return value
The inner product of <span class='code'><a href="mul.md#decl-x" class="code_param">x</a></span> and <span class='code'><a href="mul.md#decl-y" class="code_param">y</a></span>.


## Availability and Requirements

Defined for the following targets:

#### hlsl
Available in all stages.

#### glsl
Available in all stages.

#### cpp
Available in all stages.

#### cuda
Available in all stages.

#### metal
Available in all stages.

#### spirv
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
