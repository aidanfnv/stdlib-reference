---
layout: stdlib-reference
---

# concat

## Description

Return a tuple containing the values of both input tuples in order




## Signature 

<pre>
<a href="../types/tuple-0/index.md" class="code_type">Tuple</a>&lt;<a href="concat.md#typeparam-T" class="code_type">T</a>, <a href="concat.md#typeparam-U" class="code_type">U</a>&gt; <a href="concat.md">concat</a>&lt;<span class="code_keyword">each</span> <a href="concat.md#typeparam-T" class="code_type">T</a>, <span class="code_keyword">each</span> <a href="concat.md#typeparam-U" class="code_type">U</a>&gt;(
    <a href="../types/tuple-0/index.md" class="code_type">Tuple</a>&lt;<a href="concat.md#typeparam-T" class="code_type">T</a>&gt; <a href="concat.md#decl-t" class="code_param">t</a>,
    <a href="../types/tuple-0/index.md" class="code_type">Tuple</a>&lt;<a href="concat.md#typeparam-U" class="code_type">U</a>&gt; <a href="concat.md#decl-u" class="code_param">u</a>);

</pre>

## Generic Parameters

####  <a id="typeparam-T"></a>T
####  <a id="typeparam-U"></a>U

## Parameters

####  <a id="decl-t"></a>t  : [Tuple](../types/tuple-0/index.md)\<[T](../types/tuple-0/index.md#typeparam-T)\>
####  <a id="decl-u"></a>u  : [Tuple](../types/tuple-0/index.md)\<U\>


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
