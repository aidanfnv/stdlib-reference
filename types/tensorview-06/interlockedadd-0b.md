---
layout: stdlib-reference
---

# TensorView\<T\>\.InterlockedAdd

## Description





## Signature 

<pre>
<span class="code_keyword">void</span> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="interlockedadd-0b.md">InterlockedAdd</a>(
    <span class="code_keyword">uint</span> <a href="interlockedadd-0b.md#decl-index" class="code_param">index</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="interlockedadd-0b.md#decl-val" class="code_param">val</a>,
    <span class="code_keyword">out</span> <a href="index.md#typeparam-T" class="code_type">T</a> <a href="interlockedadd-0b.md#decl-oldVal" class="code_param">oldVal</a>);

<span class="code_keyword">void</span> <a href="index.md" class="code_type">TensorView</a>&lt;<a href="index.md#typeparam-T" class="code_type">T</a>&gt;.<a href="interlockedadd-0b.md">InterlockedAdd</a>&lt;<a href="interlockedadd-0b.md#decl-N" class="code_var">N</a>:<span class="code_keyword">int</span>&gt;(
    <a href="../vector/index.md" class="code_type">vector</a>&lt;<span class="code_keyword">uint</span>, <a href="interlockedadd-0b.md#decl-N" class="code_var">N</a>&gt; <a href="interlockedadd-0b.md#decl-index" class="code_param">index</a>,
    <a href="index.md#typeparam-T" class="code_type">T</a> <a href="interlockedadd-0b.md#decl-val" class="code_param">val</a>,
    <span class="code_keyword">out</span> <a href="index.md#typeparam-T" class="code_type">T</a> <a href="interlockedadd-0b.md#decl-oldVal" class="code_param">oldVal</a>);

</pre>

## Generic Parameters

####  <a id="decl-N"></a>N  : int

## Parameters

####  <a id="decl-index"></a>index  : uint
####  <a id="decl-val"></a>val  : [T](index.md#typeparam-T)
####  <a id="decl-oldVal"></a>oldVal  : [T](index.md#typeparam-T)
####  <a id="decl-index"></a>index  : [vector](../vector/index.md)\<uint, [N](../vector/index.md#decl-N)\>

## Availability and Requirements

Defined for the following targets:

#### cuda
Available in all stages.




<script>
// Fix .md links to .html when on ReadTheDocs
if (window.location.hostname.includes('readthedocs') || 
    window.location.hostname.includes('rtfd.io')) {
  document.addEventListener('DOMContentLoaded', function() {
    const links = document.querySelectorAll('a');
    links.forEach(link => {
      if (link.getAttribute('href') && link.getAttribute('href').endsWith('.md')) {
        link.href = link.href.replace(/\.md($|#|\?)/, '.html$1');
      }
    });
  });
}
</script>
